# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.4.5-custom] - 2026-03

### Fixed
- **Structured Query fields not displayed with Elasticsearch 8.x**: In ES 8.x, the `_type` field was removed from search response documents, causing all mapped field columns to disappear from Structured Query results. Fixed by falling back to `_doc` when `hit._type` is absent. No behavior change for ES 7.x users.

## [0.4.4-custom] - 2025-08
### Fixed
- fixed server removal issues

### Improved
- Redesigned Refresh button as dropdown + icon combination

### Added
- Delete Index functionality with checkbox selection
- filtering for index selector in Structured Query tab
