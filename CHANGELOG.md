# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.4.2] - 2025-01-02

### Fixed

- Resolved issue with multiple dependencies.
- Fixed broken links to [deps.rs](https://deps.rs/).

### Changed

- Split single subcommand structure into multiple substructures.
- Updated dependencies in `Cargo.lock`.
- Updated MSRV.

## [0.4.1] - 2023-12-21

### Fixed

- Changed motivation description in `README.md`s.

## [0.4.0] - 2023-12-21

### Changed

- Code refactor.

## [0.3.2] - 2023-08-21

### Added

- Added `unstable` feature.

### Fixed

- Fixed missing features information in `README.md`.

## [0.3.1] - 2023-08-19

### Fixed

- Fixed `stdin` option to conflicts only with `paths` arg.
- Fixed force binary name to `chksum`.

### Changed

- Changed usage from `name` to `value_name` for `paths` arg.

### Removed

- Removed `author` from command.

## [0.3.0] - 2023-08-18

### Added

- Added `Target` enum to better handle output printing.
- Added `#![forbid(unsafe_code)]` to forbid unsafe code.
- Added colored output.

### Fixed

- Fixed wrong link in `CHANGELOG.md`.
- Fixed missing stdin examples in `README.md` and `.cargo/README.md`.
- Fixed blank error with new version of `chksum` dependency.

### Changed

- Changed `cargo tarpaulin` command to use `--engine llvm` in GitHub Actions.
- Changed output format.
- Changed algorithms logic (can enabled or disabled via features).

### Removed

- Removed unused import.

## [0.2.0] - 2023-08-13

### Added

- Initial release.

[0.4.2]: https://github.com/chksum-rs/cli/compare/v0.4.1...v0.4.2
[0.4.1]: https://github.com/chksum-rs/cli/compare/v0.4.0...v0.4.1
[0.4.0]: https://github.com/chksum-rs/cli/compare/v0.3.2...v0.4.0
[0.3.2]: https://github.com/chksum-rs/cli/compare/v0.3.1...v0.3.2
[0.3.2]: https://github.com/chksum-rs/cli/compare/v0.3.1...v0.3.2
[0.3.1]: https://github.com/chksum-rs/cli/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/chksum-rs/cli/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/chksum-rs/cli/releases/tag/v0.2.0
