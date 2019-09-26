# Changelog

All notable changes to this project will be documented in this file.

## Release 3.0.3

**Features**
- PDK Module Conversion
- Added conn_backlog parameter
- Rubocop fixes

**Bugfixes**

**Known Issues**
- PDK metadata-json-lint is failing w/ ` uninitialized constant Semantic::Version::MAX` due to vendored gem. Need to skip metadata validation.