## [1.6.1](https://github.com/dxheroes/dx-scanner/compare/v1.6.0...v1.6.1) (2019-10-03)


### Bug Fixes

* add tests for EslintCorrectlyUsedPractice ([187f697](https://github.com/dxheroes/dx-scanner/commit/187f697))
* Allow user to add impact in object in dx config file ([22e1577](https://github.com/dxheroes/dx-scanner/commit/22e1577))
* allow user to customize configuration of DX scanner so it could be string or object ([a58f571](https://github.com/dxheroes/dx-scanner/commit/a58f571))
* Catch the error and if it's SyntaxError return PracticeEvaluationResult.unknown ([be7d1b9](https://github.com/dxheroes/dx-scanner/commit/be7d1b9))
* compare RegExp name with the package.name ([3e4a3f4](https://github.com/dxheroes/dx-scanner/commit/3e4a3f4))
* eslint practice ([6acf75f](https://github.com/dxheroes/dx-scanner/commit/6acf75f))
* Fix the condition for eslintIgnore ([54ca010](https://github.com/dxheroes/dx-scanner/commit/54ca010))
* Interface of Config; add  interface for EslintConfig and use it in PracticeContext ([70f4c9c](https://github.com/dxheroes/dx-scanner/commit/70f4c9c))
* Path for scanFor() ([c29708a](https://github.com/dxheroes/dx-scanner/commit/c29708a))
* Remove console.logs, ([08a78cf](https://github.com/dxheroes/dx-scanner/commit/08a78cf))
* Remove unnecessary logs. ([85baa4e](https://github.com/dxheroes/dx-scanner/commit/85baa4e))
* remove unnecessary type definition ([3e6fd36](https://github.com/dxheroes/dx-scanner/commit/3e6fd36))
* rename EslintConfig to PracticeConfig; return always PracticeConfig in getOverridenPractice() ([81e00cd](https://github.com/dxheroes/dx-scanner/commit/81e00cd))
* rename practice ([05c09f7](https://github.com/dxheroes/dx-scanner/commit/05c09f7))
* run on eslint/espree repo ([faa838e](https://github.com/dxheroes/dx-scanner/commit/faa838e))
* throw error if it's not a SyntaxError ([3644149](https://github.com/dxheroes/dx-scanner/commit/3644149))
* typo ([2dcb4c4](https://github.com/dxheroes/dx-scanner/commit/2dcb4c4))
* typo ([898dcc6](https://github.com/dxheroes/dx-scanner/commit/898dcc6))

# [1.6.0](https://github.com/dxheroes/dx-scanner/compare/v1.5.0...v1.6.0) (2019-10-02)


### Features

* **cli:** add update-notifier ([6733185](https://github.com/dxheroes/dx-scanner/commit/6733185)), closes [#70](https://github.com/dxheroes/dx-scanner/issues/70)

# [1.5.0](https://github.com/dxheroes/dx-scanner/compare/v1.4.2...v1.5.0) (2019-10-02)


### Features

* **cli:** add postinstall message with hint to create .dxscannerrc config file ([b652ee2](https://github.com/dxheroes/dx-scanner/commit/b652ee2))

## [1.4.2](https://github.com/dxheroes/dx-scanner/compare/v1.4.1...v1.4.2) (2019-10-02)


### Bug Fixes

* **GitService:** change join for resolve ([#74](https://github.com/dxheroes/dx-scanner/issues/74)) ([e5e4827](https://github.com/dxheroes/dx-scanner/commit/e5e4827))

## [1.4.1](https://github.com/dxheroes/dx-scanner/compare/v1.4.0...v1.4.1) (2019-09-12)


### Bug Fixes

* add new practicesWitchContext for every component in for loop. ([#46](https://github.com/dxheroes/dx-scanner/issues/46)) ([d5d50db](https://github.com/dxheroes/dx-scanner/commit/d5d50db))

# [1.4.0](https://github.com/dxheroes/dx-scanner/compare/v1.3.0...v1.4.0) (2019-08-30)


### Bug Fixes

* Improve the JSONReport. ([da37a50](https://github.com/dxheroes/dx-scanner/commit/da37a50))
* Improve the reporter interface. ([e4c0465](https://github.com/dxheroes/dx-scanner/commit/e4c0465))
* Remove reporting in the new file. ([eac49c1](https://github.com/dxheroes/dx-scanner/commit/eac49c1))


### Features

* Add JSON Reporter. ([80a0bd4](https://github.com/dxheroes/dx-scanner/commit/80a0bd4))
* Add possibility to have an output in JSON. ([3142f0f](https://github.com/dxheroes/dx-scanner/commit/3142f0f))
* Write JSON report to the new file. ([fe4fb26](https://github.com/dxheroes/dx-scanner/commit/fe4fb26))

# [1.3.0](https://github.com/dxheroes/dx-scanner/compare/v1.2.0...v1.3.0) (2019-08-27)


### Bug Fixes

* remove unnecessary condition ([d0a80fa](https://github.com/dxheroes/dx-scanner/commit/d0a80fa))
* **cli:** Remove console.log when a 404 error happens. Use debug() instead. ([d8917f3](https://github.com/dxheroes/dx-scanner/commit/d8917f3))
* Catch the auth error and handle it in index.ts instead of ScanningStrategyDetector ([af617c8](https://github.com/dxheroes/dx-scanner/commit/af617c8))
* determining private/public repo, ([f9966f5](https://github.com/dxheroes/dx-scanner/commit/f9966f5))
* Logic with accessType and tests for private repo. ([95c7036](https://github.com/dxheroes/dx-scanner/commit/95c7036))
* Remove nonsense condition. ([b5d3d99](https://github.com/dxheroes/dx-scanner/commit/b5d3d99))
* Remove unnecessary import ([e2c391a](https://github.com/dxheroes/dx-scanner/commit/e2c391a))
* Remove unnecessary piece of code ([8e0e42a](https://github.com/dxheroes/dx-scanner/commit/8e0e42a))
* Remove unused import. ([c3b22d0](https://github.com/dxheroes/dx-scanner/commit/c3b22d0))
* Remove unused interface. ([0f7fe62](https://github.com/dxheroes/dx-scanner/commit/0f7fe62))
* Remove unused interface. ([bf5b5c5](https://github.com/dxheroes/dx-scanner/commit/bf5b5c5))
* Remove unused variable. ([f0031b1](https://github.com/dxheroes/dx-scanner/commit/f0031b1))
* Tests for private repos. ([1bb96ed](https://github.com/dxheroes/dx-scanner/commit/1bb96ed))
* throw right error ([4f83feb](https://github.com/dxheroes/dx-scanner/commit/4f83feb))
* throwing error ([9696f91](https://github.com/dxheroes/dx-scanner/commit/9696f91))


### Features

* **cli:** add possibility to insert AT after running scanner if the AT was not provided. ([47353dd](https://github.com/dxheroes/dx-scanner/commit/47353dd))

# [1.2.0](https://github.com/dxheroes/dx-scanner/compare/v1.1.4...v1.2.0) (2019-08-21)


### Features

* **CI:** add scripts to run on travis ([#39](https://github.com/dxheroes/dx-scanner/issues/39)) ([c701407](https://github.com/dxheroes/dx-scanner/commit/c701407))

## [1.1.4](https://github.com/dxheroes/dx-scanner/compare/v1.1.3...v1.1.4) (2019-08-20)


### Bug Fixes

* **practices:** add dependsOn in related practices ([#38](https://github.com/dxheroes/dx-scanner/issues/38)) ([019ee6a](https://github.com/dxheroes/dx-scanner/commit/019ee6a))

## [1.1.3](https://github.com/dxheroes/dx-scanner/compare/v1.1.2...v1.1.3) (2019-08-19)


### Bug Fixes

* move misuesed devDependencies to dependencies ([#37](https://github.com/dxheroes/dx-scanner/issues/37)) ([62fcc4f](https://github.com/dxheroes/dx-scanner/commit/62fcc4f))

## [1.1.2](https://github.com/dxheroes/dx-scanner/compare/v1.1.1...v1.1.2) (2019-08-19)


### Bug Fixes

* remote url is ssh ([f9d57bc](https://github.com/dxheroes/dx-scanner/commit/f9d57bc))
* **cli:** set relative path to correct index.js file for real runtime ([4bc4051](https://github.com/dxheroes/dx-scanner/commit/4bc4051))

## [1.1.1](https://github.com/dxheroes/dx-scanner/compare/v1.1.0...v1.1.1) (2019-08-16)


### Bug Fixes

* **README:** fix command for installing ([#29](https://github.com/dxheroes/dx-scanner/issues/29)) ([81fff27](https://github.com/dxheroes/dx-scanner/commit/81fff27))

# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed

- Works on Windows
- Possible to develop on Windows

## [1.0.0] - 2019-07-31

### Added

- First version of DX Scanner
