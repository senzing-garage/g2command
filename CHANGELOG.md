# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
[markdownlint](https://dlaa.me/markdownlint/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.3.4] - 2023-10-02

### Changed in 2.3.4

- In `Dockerfile`, updated FROM instruction to `senzing/senzingapi-tools:3.7.1`

## [2.3.3] - 2023-09-20

### Fixed in 2.3.3

- Removed duplicated argument parser for replaceRecordWithInfo

## [2.3.2] - 2023-08-18

### Changed in 2.3.2

- In `Dockerfile`, updated FROM instruction to `senzing/senzingapi-tools:3.6.0`
- Added internal flags

## [2.3.1] - 2023-06-22

### Changed in 2.3.1

- Add function for search-by-attributes that uses search-profiles.

## [2.3.0] - 2023-05-02

### Added in 2.3.0

- Improved help and help for commands
- Tab autocomplete for commands that specify files
- Tab autocomplete for engine flags
- Engine flags can now be specified as an int or their string names
- JSON responses can now be formatted and changed between json and jsonl
- JSON formatting adds color
- Improved usage details on argument parsers
- New CLI argument to disable color output
- Can send last response message to clipboard or a file

### Fixed in 2.3.0

- exportJSONEntityReport & exportCSVEntityReport, could exhaust memory and abend
- Replacing default config wasn't restarting engines
- Misc fixes

## [2.2.4] - 2023-04-04

### Changed in 2.2.4

- In `Dockerfile`, updated FROM instruction to `senzing/senzingapi-tools:3.5.0`

## [2.2.3] - 2022-11-16

### Changed in 2.2.3

- Add getDBInfo command

## [2.2.2] - 2022-10-11

### Changed in 2.2.2

- In `Dockerfile`, updated FROM instruction to `senzing/senzingapi-tools:3.3.1`

## [2.2.1] - 2022-09-28

### Changed in 2.2.1

- In `Dockerfile`, updated FROM instruction to `senzing/senzingapi-tools:3.3.0`

## [2.2.0] - 2022-08-25

### Changed in 2.2.0

- In `Dockerfile`, bump from `senzing/senzing-base:1.6.8` to `senzing/senzingapi-runtime:3.2.0`

## [2.1.1] - 2022-08-11

### Added in 2.1.1

- Improved support for `SENZING_ENGINE_CONFIGURATION_JSON`

## [2.1.0] - 2022-08-04

### Added in 2.1.0

- Support for `SENZING_ENGINE_CONFIGURATION_JSON`

### Deleted in 2.1.0

- Dockerfile CMD instruction

## [2.0.5] - 2022-07-06

### Added to 2.0.5

- Make most G2Diagnostic API calls hidden from the regular command list.

## [2.0.4] - 2022-06-08

### Added to 2.0.4

- Alter the G2IniParams import, after it was removed from the SDK.

## [2.0.3] - 2022-05-25

### Added to 2.0.3

- Migrate Dockerfile from [docker-g2command](https://github.com/Senzing/docker-g2command) to this repository

## [2.0.2] - 2022-05-19

### Added to 2.0.2

- Make the function for getting a redo record hidden

## [2.0.1] - 2022-05-16

### Added to 2.0.1

- Added function for getting a redo record

## [2.0.0] - 2022-05-04

### Added to 2.0.0

- Support SenzingAPI 3.0.0

## [1.19.0] - 2021-07-13

### Added to 1.19.0

- Shipped with SenzingAPI 2.8.0

## [1.18.0] - 2021-05-17

### Added to 1.18.0

- Shipped with SenzingAPI 2.6.0

## [1.17.0] - 2020-12-15

### Added to 1.17.0

- Shipped with SenzingAPI 2.3.0

## [1.16.1] - 2020-10-23

### Added to 1.16.1

- Shipped with SenzingAPI 2.2.2

## [1.16.0] - 2020-09-30

### Added to 1.16.0

- Shipped with SenzingAPI 2.2.1

## [1.15.0] - 2020-07-16

### Added to 1.15.0

- Shipped with SenzingAPI 2.0.0

## [1.14.1] - 2020-05-20

### Added to 1.14.1

- Shipped with SenzingAPI 1.15.3

## [1.14.0] - 2020-04-20

### Added to 1.14.0

- Shipped with SenzingAPI 1.15.0

## [1.13.0] - 2020-02-06

### Added to 1.13.0

- Shipped with SenzingAPI 1.14.0

## [1.12.0] - 2019-11-25

### Added to 1.12.0

- Shipped with SenzingAPI 1.13.1

## [1.11.0] - 2019-10-16

### Added to 1.11.0

- Shipped with SenzingAPI 1.12.0

## [1.10.0] - 2019-09-03

### Added to 1.10.0

- Shipped with SenzingAPI 1.11.0

## [1.9.1] - 2019-08-02

### Added to 1.9.1

- Shipped with SenzingAPI 1.10.1

## [1.9.0] - 2019-07-09

### Added to 1.9.0

- Shipped with SenzingAPI 1.10.0

## [1.8.0] - 2019-06-04

### Added to 1.8.0

- Shipped with SenzingAPI 1.9.0

## [1.7.0] - 2019-05-08

### Added to 1.7.0

- Shipped with SenzingAPI 1.8.0

## [1.6.1] - 2019-04-09

### Added to 1.6.1

- Shipped with SenzingAPI 1.7.1

## [1.6.0] - 2019-04-05

### Added to 1.6.0

- Shipped with SenzingAPI 1.7.0

## [1.5.0] - 2019-03-02

### Added to 1.5.0

- Shipped with SenzingAPI 1.6.0

## [1.4.0] - 2019-01-31

### Added to 1.4.0

- Shipped with SenzingAPI 1.5.0

## [1.3.0] - 2018-12-07

### Added to 1.3.0

- Shipped with SenzingAPI 1.4.0

## [1.2.0] - 2018-10-02

### Added to 1.2.0

- Shipped with SenzingAPI 1.3.0

## [1.1.0] - 2018-09-30

### Added to 1.1.0

- Shipped with SenzingAPI 1.2.0

## [1.0.0] - 2018-09-18

### Added to 1.0.0

- Shipped with SenzingAPI 1.1.0
