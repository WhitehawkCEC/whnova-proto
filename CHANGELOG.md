# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.5.6](https://github.com/whitehawkcec/whnova-proto/compare/0.5.5...0.5.6) (2026-04-23)


### Features

* **proto/api-riskwise-client:** add `REQUIRED` ([f33e4ca](https://github.com/whitehawkcec/whnova-proto/commit/f33e4ca3ba6ea5df0082ff18443cdab84559dae4))
* **proto/api-riskwise-client:** add `resources.external_users__0__roles.v2` ([80260a1](https://github.com/whitehawkcec/whnova-proto/commit/80260a1f0f571375280915c10c8f015fd26ab0a6))
* **proto/core:** add `user.external.v1` ([845564e](https://github.com/whitehawkcec/whnova-proto/commit/845564ef0eb90accdb92389883f084ec82eab8d9))

### [0.5.5](https://github.com/WhitehawkCEC/whnova-proto/compare/0.5.4...0.5.5) (2026-04-23)

### [0.5.4](https://github.com/WhitehawkCEC/whnova-proto/compare/0.5.3...0.5.4) (2026-04-22)


### Features

* **proto:** add product ([524cfb8](https://github.com/WhitehawkCEC/whnova-proto/commit/524cfb8c7025461456f40b7508c02238f0d0ec58))
* **proto:** add product catalog service ([047ff6f](https://github.com/WhitehawkCEC/whnova-proto/commit/047ff6fd96de4c46422ad4b1e23ec65ef969c8cf))
* **proto:** add product checkout service ([0f6909c](https://github.com/WhitehawkCEC/whnova-proto/commit/0f6909ce4330311f1f9cebefe9c79c931fdc4eb7))


### Bug Fixes

* **proto:** deprecate credit checkout service ([34e5528](https://github.com/WhitehawkCEC/whnova-proto/commit/34e5528bb0f4e8c1c7e1f979088b7872cb7e8703))

### [0.5.3](https://github.com/whitehawkcec/whnova-proto/compare/0.5.2...0.5.3) (2026-04-20)

### Features

- **proto/api-riskwise-client:** add `full_questionnaire_submissions.v1` `created_at` ([c646fc0](https://github.com/whitehawkcec/whnova-proto/commit/c646fc0504a4260bbc94bd33af11406f6d008410))
- **proto/api-riskwise-client:** add `resources.external_users__0__roles.v1` ([3302241](https://github.com/whitehawkcec/whnova-proto/commit/330224115b1ff43c3eb61ac3e8b893b032bab82f))
- **proto/api-riskwise-client:** add `resources.external_users.v1` ([6d304df](https://github.com/whitehawkcec/whnova-proto/commit/6d304df8df4ca7b568cd547d3b39825d6830e5e4))
- **proto/api-riskwise-client:** add `resources.roles.v1` ([03848ac](https://github.com/whitehawkcec/whnova-proto/commit/03848ac1865e40559ce039f4a5829577fa7b6456))
- **proto/core:** add `iam.v1` ([944fbdc](https://github.com/whitehawkcec/whnova-proto/commit/944fbdc903945e2c7aef8dcd9b54889144bd9a1c))

### [0.5.2](https://github.com/WhitehawkCEC/whnova-proto/compare/0.5.1...0.5.2) (2026-04-07)

### Features

- **proto:** add credit checkout service ([e5c971a](https://github.com/WhitehawkCEC/whnova-proto/commit/e5c971ad56b47f44a3df579e2fb8ffdec1e57c00))

### [0.5.1](https://github.com/whitehawkcec/whnova-proto/compare/0.5.0...0.5.1) (2026-04-06)

### Features

- **proto/api-riskwise-client:** add `questionnaire_meta.v1` `GetResponse` `risk_level_bands` ([2ea5868](https://github.com/whitehawkcec/whnova-proto/commit/2ea586878cd7eb55943b385a9139ccd3b56f9c48))

## [0.5.0](https://github.com/whitehawkcec/whnova-proto/compare/0.4.8...0.5.0) (2026-03-31)

### ⚠ BREAKING CHANGES

- **proto/core:** switch `int32` -> `double` for scores

### Features

- **proto/core:** switch `int32` -> `double` for scores ([25b4be7](https://github.com/whitehawkcec/whnova-proto/commit/25b4be7694dd591059da65a2469488469de2c883))

### [0.4.8](https://github.com/whitehawkcec/whnova-proto/compare/0.4.7...0.4.8) (2026-03-31)

### Features

- **proto/api-riskwise-client:** add `full_questionnaire_submissions.v1` `Read` ([dfff0e1](https://github.com/whitehawkcec/whnova-proto/commit/dfff0e151674a47478256764784d88f47fea3d6a))
- **proto/api-riskwise-client:** include risk score/level for each submission ([3fb48a6](https://github.com/whitehawkcec/whnova-proto/commit/3fb48a6ba547220051e7a2cb02fa1ca69b0124d9))
- **proto/core:** add `RiskLevel` ([bd75ac6](https://github.com/whitehawkcec/whnova-proto/commit/bd75ac648f989f5653c42cf1b157e34f2defb51f))
- **proto/core:** add `RiskScore` ([a63adf5](https://github.com/whitehawkcec/whnova-proto/commit/a63adf5e327a87e65ce4c13f4676a6fbcb975c31))

### [0.4.7](https://github.com/whitehawkcec/whnova-proto/compare/0.4.6...0.4.7) (2026-03-29)

### Features

- **api-riskwise-client:** add `resources.full_questionnaire_submissions__0__assessment_pdf.v1` ([919c07f](https://github.com/whitehawkcec/whnova-proto/commit/919c07f3140e97071a069ea2f0372e186ef00025))
- **core:** add `indirect_file.v1` ([1780a55](https://github.com/whitehawkcec/whnova-proto/commit/1780a553c9adb0a2da853d14aa3f4deb7c6096e9))
- **proto/api-riskwise-client:** add `resources.questionnaire_meta.v1` ([d3a75b4](https://github.com/whitehawkcec/whnova-proto/commit/d3a75b48211419f0c09b5f4600a74e7fc44ab1a8))
- **proto/core:** add `QuestionCode` ([d019417](https://github.com/whitehawkcec/whnova-proto/commit/d0194175c1ee7648fa5ff0614083c10b942b9466))

### [0.4.6](https://github.com/WhitehawkCEC/whnova-proto/compare/0.4.5...0.4.6) (2026-03-26)

### Bug Fixes

- **proto:** add action for updating an answer ([5bad41f](https://github.com/WhitehawkCEC/whnova-proto/commit/5bad41fd64e388b75e60428f53a1b271082727ed))

### [0.4.5](https://github.com/WhitehawkCEC/whnova-proto/compare/0.4.4...0.4.5) (2026-03-26)

### Features

- **proto:** add endpoint for organization audit log ([33ccd51](https://github.com/WhitehawkCEC/whnova-proto/commit/33ccd5108b2bc8f8a97cb5def077e624a05223d2))

### [0.4.4](https://github.com/WhitehawkCEC/whnova-proto/compare/0.4.3...0.4.4) (2026-03-16)

### [0.4.3](https://github.com/WhitehawkCEC/whnova-proto/compare/0.4.2...0.4.3) (2026-03-16)

### Bug Fixes

- **proto:** IsoDateTime instead of Timestamp. add lint ignore ([78208e8](https://github.com/WhitehawkCEC/whnova-proto/commit/78208e8e36f4bc385d6b4fa8e10dbb20b97ca537))

### [0.4.2](https://github.com/WhitehawkCEC/whnova-proto/compare/0.4.1...0.4.2) (2026-03-16)

### Bug Fixes

- **proto:** file name ([6527346](https://github.com/WhitehawkCEC/whnova-proto/commit/6527346c87c947cf75164f9deaa39cf94debcb56))

### [0.4.1](https://github.com/WhitehawkCEC/whnova-proto/compare/0.4.0...0.4.1) (2026-03-11)

### Bug Fixes

- **proto:** package name ([7a83e88](https://github.com/WhitehawkCEC/whnova-proto/commit/7a83e88879cc02b69342a8bd3821bac1a1ba64b0))

## [0.4.0](https://github.com/WhitehawkCEC/whnova-proto/compare/0.3.2...0.4.0) (2026-03-11)

### ⚠ BREAKING CHANGES

- **proto:** remove service `main_questionnaire_submissions.v1`

### Features

- **proto:** add endpoint for user attribution (audit log) ([2201b1e](https://github.com/WhitehawkCEC/whnova-proto/commit/2201b1e93a09540c82dbf8f8808ebee9a6290cad))
- **proto:** remove service `main_questionnaire_submissions.v1` ([59a3783](https://github.com/WhitehawkCEC/whnova-proto/commit/59a3783d593ecc857b90ee7e83d0d91b21c3838a))

### [0.3.2](https://github.com/whitehawkcec/whnova-proto/compare/0.3.1...0.3.2) (2026-02-26)

### Features

- **proto:** add client `full_questionnaire_submissions/v1` ([cedea0f](https://github.com/whitehawkcec/whnova-proto/commit/cedea0fc93bcaf92241d9703453ac1823049d6ac))

### [0.3.1](https://github.com/whitehawkcec/whnova-proto/compare/0.3.0...0.3.1) (2026-02-26)

### Features

- **proto:** add `main_questionnaire_submissions/v1` `List` ([30db813](https://github.com/whitehawkcec/whnova-proto/commit/30db813ed5b3de720523567374f6a3e159dad793))
- **proto:** add `QuestionnaireSubmissionId` ([30f7647](https://github.com/whitehawkcec/whnova-proto/commit/30f7647cb00c3afde43c9e6e6514cd9ec94af43c))
- **proto:** return generated ID after create ([80764cc](https://github.com/whitehawkcec/whnova-proto/commit/80764ccf54e572574eee52a10e6ef32729f0bcdb))

## [0.3.0](https://github.com/whitehawkcec/whnova-proto/compare/0.2.1...0.3.0) (2026-02-23)

### ⚠ BREAKING CHANGES

- **proto/core:** change questionnaire messages

### Features

- **proto/core:** add `OrgId` ([cc03133](https://github.com/whitehawkcec/whnova-proto/commit/cc031335da2a18a259bd4c5ddf673ba2b2e82a8e))
- **proto/core:** add questionnaire messages ([c85d5f1](https://github.com/whitehawkcec/whnova-proto/commit/c85d5f12c1ca504c3185a5bf0bb3a78dbce58c29))
- **proto/core:** change questionnaire messages ([0ded273](https://github.com/whitehawkcec/whnova-proto/commit/0ded2734d31766c6200ccc1fd68091adc458f603))
- **proto:** add endpoints for lead questionnaire ([f238357](https://github.com/whitehawkcec/whnova-proto/commit/f2383576efa0f5120897b1b52744f24d106bad09))
- **proto:** add endpoints for lead questionnaire answers ([7c93bc9](https://github.com/whitehawkcec/whnova-proto/commit/7c93bc976ebd448340c5de3c456934b26a86d650))
- **proto:** add endpoints for lead questionnaire progress ([8f72852](https://github.com/whitehawkcec/whnova-proto/commit/8f7285272801f203b5c70eedc4a018e54d037ac1))
- **proto:** add endpoints for main questionnaire ([0c81000](https://github.com/whitehawkcec/whnova-proto/commit/0c8100097106d2052cda080c0433e3a25d16c488))
- **proto:** add endpoints for main questionnaire answers ([65c927e](https://github.com/whitehawkcec/whnova-proto/commit/65c927e061a7ca758923e89d73ed3d44069a3414))
- **proto:** add endpoints for main questionnaire progress ([e25fd86](https://github.com/whitehawkcec/whnova-proto/commit/e25fd865dad0f4f83209ea063100137b9b7013df))
- **proto:** add endpoints for main questionnaire submission ([3ed68f6](https://github.com/whitehawkcec/whnova-proto/commit/3ed68f66a346de3b1813f65acd66dbde825b3ac2))

### [0.2.1](https://github.com/whitehawkcec/whnova-proto/compare/0.2.0...0.2.1) (2026-01-28)

## [0.2.0](https://github.com/whitehawkcec/whnova-proto/compare/0.1.2...0.2.0) (2026-01-28)

### ⚠ BREAKING CHANGES

- **proto:** downgrade to edition 2023.

### Features

- **proto:** downgrade to edition 2023. ([29f7a90](https://github.com/whitehawkcec/whnova-proto/commit/29f7a902afade26bf22bc05049fd6bc1f353b399))

### [0.1.2](https://github.com/whitehawkcec/whnova-proto/compare/0.1.1...0.1.2) (2026-01-28)

### [0.1.1](https://github.com/whitehawkcec/whnova-proto/compare/0.1.0...0.1.1) (2026-01-28)
