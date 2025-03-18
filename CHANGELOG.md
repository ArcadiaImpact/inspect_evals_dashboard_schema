# Changelog

All notable changes to the `inspect_evals_dashboard_schema` package will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.1] - 2025-03-17

### Added

- Added `py.typed` marker file to enable proper type checking support

### Changed

- Updated schema version from "1.0" to "1.1"
- Made `reductions` field optional in the `DashboardLog` class

### Fixed

- Type checking issues with the package by adding `py.typed` marker

## [0.1.0] - 2025-03-12

### Added

- Initial release of the schema package
- Defined core schema classes:
  - `ModelMetadata`: Metadata about models used in evaluations
  - `EvalMetadata`: Metadata about evaluations
  - `DashboardLog`: Main log structure for dashboard visualization
- Added basic project structure with pyproject.toml
