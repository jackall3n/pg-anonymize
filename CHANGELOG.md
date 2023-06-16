# 1.0.0 (2023-06-16)


### Bug Fixes

* small error ([#2](https://github.com/jackall3n/pg-anonymize/issues/2)) ([a6cb7e2](https://github.com/jackall3n/pg-anonymize/commit/a6cb7e2bd1beb71f23eb50421978f5ad074308c0))
* **stdout:** wait for output to be processed instead of buffering ([#29](https://github.com/jackall3n/pg-anonymize/issues/29)) ([1146187](https://github.com/jackall3n/pg-anonymize/commit/11461870674b65be83f2a9b6ba07b9162c2c19b1))
* typo ([#1](https://github.com/jackall3n/pg-anonymize/issues/1)) ([ae32e6b](https://github.com/jackall3n/pg-anonymize/commit/ae32e6b6e8a18bb54fca445b24cffd4fdc2951c7))
* various fixes ([297da61](https://github.com/jackall3n/pg-anonymize/commit/297da61cb9354a7f4588ebb290366f7fd46742ee))


### Features

* add --skip and --preserve-null support, with chalk for logging ([ecc6818](https://github.com/jackall3n/pg-anonymize/commit/ecc6818a96a0bcaa4e5142a82735835fdae0a5ab))
* add custom extension ([#5](https://github.com/jackall3n/pg-anonymize/issues/5)) ([874a602](https://github.com/jackall3n/pg-anonymize/commit/874a60223357f3d74db52599944bcede90cb1d38))
* add support to specify tables in list of columns ([#13](https://github.com/jackall3n/pg-anonymize/issues/13)) ([bc6638d](https://github.com/jackall3n/pg-anonymize/commit/bc6638de24632cb0bee9059e25e688f19f9b2c6d))
* allow for passthrough of extra args to pg_dump ([#26](https://github.com/jackall3n/pg-anonymize/issues/26)) ([776b5be](https://github.com/jackall3n/pg-anonymize/commit/776b5be4efa8196b26d77b479329eb04033bc384))
* new option to read replacements from a file ([#18](https://github.com/jackall3n/pg-anonymize/issues/18)) ([a7c6441](https://github.com/jackall3n/pg-anonymize/commit/a7c644139f74616c0c4be79d06514e3b046f62ce))
* output can be stdout so you can pipe it to other commands ([#19](https://github.com/jackall3n/pg-anonymize/issues/19)) ([11e46ce](https://github.com/jackall3n/pg-anonymize/commit/11e46ce8ac8786d08401da2c27ef7089aa783905))
* table name to extension functions ([#8](https://github.com/jackall3n/pg-anonymize/issues/8)) ([9f0a8f8](https://github.com/jackall3n/pg-anonymize/commit/9f0a8f88ab443a1991136a475ea95e528799aff8))

# [0.7.0](https://github.com/rap2hpoutre/pg-anonymize/compare/v0.6.0...v0.7.0) (2023-03-20)


### Features

* add --skip and --preserve-null support, with chalk for logging ([ecc6818](https://github.com/rap2hpoutre/pg-anonymize/commit/ecc6818a96a0bcaa4e5142a82735835fdae0a5ab))

# [0.6.0](https://github.com/rap2hpoutre/pg-anonymize/compare/v0.5.1...v0.6.0) (2022-07-08)


### Features

* allow for passthrough of extra args to pg_dump ([#26](https://github.com/rap2hpoutre/pg-anonymize/issues/26)) ([776b5be](https://github.com/rap2hpoutre/pg-anonymize/commit/776b5be4efa8196b26d77b479329eb04033bc384))

## [0.5.1](https://github.com/rap2hpoutre/pg-anonymize/compare/v0.5.0...v0.5.1) (2022-05-06)


### Bug Fixes

* **stdout:** wait for output to be processed instead of buffering ([#29](https://github.com/rap2hpoutre/pg-anonymize/issues/29)) ([1146187](https://github.com/rap2hpoutre/pg-anonymize/commit/11461870674b65be83f2a9b6ba07b9162c2c19b1))

# [0.5.0](https://github.com/rap2hpoutre/pg-anonymize/compare/v0.4.0...v0.5.0) (2022-03-13)


### Features

* add support to specify tables in list of columns ([#13](https://github.com/rap2hpoutre/pg-anonymize/issues/13)) ([bc6638d](https://github.com/rap2hpoutre/pg-anonymize/commit/bc6638de24632cb0bee9059e25e688f19f9b2c6d))
* new option to read replacements from a file ([#18](https://github.com/rap2hpoutre/pg-anonymize/issues/18)) ([a7c6441](https://github.com/rap2hpoutre/pg-anonymize/commit/a7c644139f74616c0c4be79d06514e3b046f62ce))
* output can be stdout so you can pipe it to other commands ([#19](https://github.com/rap2hpoutre/pg-anonymize/issues/19)) ([11e46ce](https://github.com/rap2hpoutre/pg-anonymize/commit/11e46ce8ac8786d08401da2c27ef7089aa783905))
* table name to extension functions ([#8](https://github.com/rap2hpoutre/pg-anonymize/issues/8)) ([9f0a8f8](https://github.com/rap2hpoutre/pg-anonymize/commit/9f0a8f88ab443a1991136a475ea95e528799aff8))
