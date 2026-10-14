# Changelog

All notable changes to this project are documented in this file.

The format is based on Keep a Changelog (https://keepachangelog.com/en/1.1.0/),
and this project adheres to Semantic Versioning (https://semver.org/).

## [Unreleased]

### Added
- [New capability, one line per change]

## [2.4.0] - 2026-09-15

### Added
- Invoice approvals: reviewers can approve, reject, or request changes (#1452)

### Changed
- CSV exports now include the invoice currency column (#1438)

### Deprecated
- The v1 invoices endpoint. It will be removed in 3.0.0; use v2 instead (#1447)

### Fixed
- Long invoices no longer overlap the PDF footer (#1440)

### Security
- Upgraded the PDF renderer to patch a file-parsing vulnerability (#1444)

## [2.3.1] - 2026-08-28

### Fixed
- Date filters now respect your workspace time zone (#1419)

[Unreleased]: https://github.com/your-org/your-repo/compare/v2.4.0...HEAD
[2.4.0]: https://github.com/your-org/your-repo/compare/v2.3.1...v2.4.0
[2.3.1]: https://github.com/your-org/your-repo/compare/v2.3.0...v2.3.1