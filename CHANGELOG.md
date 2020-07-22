# [0.11.0](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.10.0...v0.11.0) (2020-07-15)


### Features

* **tms support:** enabled a tmsUrl to be setup and linked on the report. Updated README ([a9dbb72](https://github.com/ryparker/jest-circus-allure-environment/commit/a9dbb72578e35a576ac2a39d70eb8d863bc1b47d))

# [0.10.0](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.9.0...v0.10.0) (2020-07-15)


### Bug Fixes

* **fixed .git repo link:** reconfigured .git/config to use renamed repo ([f76b77f](https://github.com/ryparker/jest-circus-allure-environment/commit/f76b77f6c0853257e39924ba45004b375f70819a))


### Features

* **allure reporter:** implemented docblock pragma parsing which will be used to add more reporting ([7997047](https://github.com/ryparker/jest-circus-allure-environment/commit/79970479b8a5fa651da24144a7c7bcc9bb05843c))

# [0.9.0](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.8.0...v0.9.0) (2020-07-12)


### Features

* **environmentinfo:** added environmentInfo reporting. Improved test case reporting ([9ff3ce2](https://github.com/ryparker/jest-circus-allure-environment/commit/9ff3ce20940c89b326d75a9b0991ffb331763ba8))

# [0.8.0](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.7.2...v0.8.0) (2020-07-08)


### Features

* **project-wide:** added Jest specific categories, and improved error catching ([5c4ae36](https://github.com/ryparker/jest-circus-allure-environment/commit/5c4ae36c51f67aafcd1190cc6171b76bc7608986))

## [0.7.2](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.7.1...v0.7.2) (2020-07-08)


### Bug Fixes

* reconnected results dir option ([24df569](https://github.com/ryparker/jest-circus-allure-environment/commit/24df56929996c9ed6dfdc493781a77042a342074))

## [0.7.1](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.7.0...v0.7.1) (2020-07-08)


### Bug Fixes

* reverted environmentInfo feat ([9bf8dd2](https://github.com/ryparker/jest-circus-allure-environment/commit/9bf8dd25468fd3655bea228b6cb4eb553bc637bb))
* **allure-node-environment:** fixed typo ([d8592ed](https://github.com/ryparker/jest-circus-allure-environment/commit/d8592ede1dd95cd2fc621a2eccb8099e2ba26991))

# [0.7.0](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.6.1...v0.7.0) (2020-07-08)


### Features

* **allurereporter:** accepting environmentInfo and jiraUrl from jest environmentt options ([b2ae7ab](https://github.com/ryparker/jest-circus-allure-environment/commit/b2ae7abb07e21325cf9b6c0adfdee14179be0180))

## [0.6.1](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.6.0...v0.6.1) (2020-07-07)


### Bug Fixes

* **console logs:** fixed null docblockPragma console log condition ([bc41d2b](https://github.com/ryparker/jest-circus-allure-environment/commit/bc41d2bbbd21552f8f3b40824063c7184d3d4417))

# [0.6.0](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.5.0...v0.6.0) (2020-07-07)


### Features

* **package-wide:** exporting StepWrapper type and disabled some unnecessary console logs ([5763d91](https://github.com/ryparker/jest-circus-allure-environment/commit/5763d910c3e1a2e5c89c6ae085acab31cd21e190))

# [0.5.0](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.4.2...v0.5.0) (2020-07-07)


### Features

* **step-interface:** improved steps interface to support attachments and more ([a84c481](https://github.com/ryparker/jest-circus-allure-environment/commit/a84c4817bbd2bb4f0e428108891bfa7b87bec73e))

## [0.4.2](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.4.1...v0.4.2) (2020-07-06)


### Bug Fixes

* **allure-reporter.ts:** fixed null pointer exception ([0bbd59a](https://github.com/ryparker/jest-circus-allure-environment/commit/0bbd59ae5ca51c0fe44513bfebf62d271fe4a554))

## [0.4.1](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.4.0...v0.4.1) (2020-07-06)


### Bug Fixes

* **allure-reporter.ts:** fixed Snapshot failure handling ([4922775](https://github.com/ryparker/jest-circus-allure-environment/commit/492277591666964d6f60ad13eee021e60eca47ed))

# [0.4.0](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.3.0...v0.4.0) (2020-07-06)


### Features

* **project wide:** added support for the global "allure" report helper. Added better types support ([3cc3adc](https://github.com/ryparker/jest-circus-allure-environment/commit/3cc3adc70364a645b3d1051fa5a9210f68decc06))

# [0.3.0](https://github.com/ryparker/jest-circus-allure-environment/compare/v0.2.0...v0.3.0) (2020-07-06)


### Bug Fixes

* **package.json:** added dev dep @semantic-release/changelog ([df3f96c](https://github.com/ryparker/jest-circus-allure-environment/commit/df3f96c4d3260e65f91d4e969efa4f1b5c25b1b9))
* **package.json:** added dev dep @semantic-release/git for CI ([0f52366](https://github.com/ryparker/jest-circus-allure-environment/commit/0f52366e60f53803e2a2a3aee3d4bb50f6944a92))


### Features

* **package.json:** renamed npm package, better declarations, removed logs ([0d2cae0](https://github.com/ryparker/jest-circus-allure-environment/commit/0d2cae06f9314d414bc3075fbf0d32f8ab05c856))