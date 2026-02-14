# CLAUDE.md

Protobuf / gRPC API definitions repo, published to [Buf Schema Registry](https://buf.build/whnova).

## Commands

```bash
pnpm exec buf lint                                       # Lint (STANDARD rules)
pnpm exec buf breaking --against .git#branch=main        # Breaking change detection (FILE level)
pnpm exec buf format -w                                  # Format protos
pnpm exec prettier --write '**/*.{js,yml,yaml,json,md}'  # Format everything else
pnpm run release                                         # Release via standard-version
```

## Conventions

- Edition: `edition = "2023"` (not proto3)
- Messages in `message.proto`, RPCs in `service.proto`
- Directory structure mirrors package path: `proto/<module>/<full>/<package>/<path>/v1/`
- Core packages: `whnova.core.<domain>.v1`
- API packages: `whnova.api.<name>.resources.<resource>.v<version>`
- `__0__` in paths = path parameter (e.g., `organizations__0__assessments` → `/organizations/{org_id}/assessments`)

## Modules (buf.yaml v2)

- `proto/core/` → `buf.build/whnova/whnova-core` — shared core types
- `proto/api-riskwise-admin/` → `buf.build/whnova/whnova-api-riskwise-admin` — RiskWise Admin API
- Tags: no `v` prefix (e.g., `0.2.1`)
