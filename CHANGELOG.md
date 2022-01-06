# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- `artefacts_store_directory` now creates missing directories in path and now doesn't require path
  ending in `/`

### Fixed
- Now properly passing `run_params` to validations

## [v0.2.0] - 2021-10-01
### Added
- Implement skipping validation-model combinations if already have results for that pair.
- Run time check that validation-model combinations don't return results that contain a privileged
  key name.

### Changed
- BREAKING: Decouple results store and artefacts store in `run` interface. Changes `run` arguments.


## [v0.1.0] - 2021-09-09
### Added
- Registry interfaces
- Implement main run and store interfaces
- Typing for core entities
- Implement artefacts directory functionality
- Add proper README

## [v0.0.1-alpha.1] - 2021-07-13
### Added
- Stub module

[Unreleased]: https://github.com/datavaluepeople/kotsu/compare/v0.2.0...HEAD
[v0.2.0]: https://github.com/datavaluepeople/kotsu/compare/v0.1.0...v0.2.0
[v0.1.0]: https://github.com/datavaluepeople/kotsu/compare/v0.0.1-alpha.1...v0.1.0
[v0.0.1-alpha.1]: https://github.com/datavaluepeople/kotsu/releases/tag/v0.0.1-alpha.1
