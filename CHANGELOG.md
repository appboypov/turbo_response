# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2025-01-06

### Added
- Type-safe response wrapper for success and failure states
- Pattern matching with `when` and `maybeWhen` methods
- Transformation methods: `mapSuccess`, `mapFail`, and `andThen`
- Utility methods: `unwrap`, `unwrapOr`, and `ensure`
- Static utility methods: `traverse` and `sequence`
- Support for async operations in `mapSuccess` and `andThen`
- Static `throwFail` method for creating and throwing failures
- Title and message support for empty responses
- Platform-agnostic support (works with pure Dart projects)
- Zero Flutter dependencies for Dart-only projects
- All features from previous versions (0.1.0 - 0.2.6)

### Changed
- Renamed internal classes for better code organization
- Updated method names for better clarity and consistency
- Enhanced documentation with clearer descriptions
- Improved parameter names in IDE tooltips
- Better empty response handling with descriptive information
- Enhanced documentation formatting
- Renamed `throwFail` to `throwWhenFail` for better clarity
- Moved Flutter to dev_dependencies for Dart compatibility
