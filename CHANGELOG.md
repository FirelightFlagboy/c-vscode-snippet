# Change Log

All notable changes to the "c-snippet" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

## 0.0.4 2019-10-21
### Changed
- `description` field in [snippet](snippets/snippets.json)
- add a list of available `snippets` in README

## [0.1.0] - 2019-01-14
### Modified
- split `snippets/snippets.json` into independent file `include_guard.json`, `main.json`, `typedef_struct.json`

### Added
- `include_guard.json` contains the include guard scheme for header file
- `main.json` contains the sheme for `main` function with *argc* and *argv*
- `typedef_struct.json` contains the sheme for struct declaration prefixed with `s_` and `t_` for **the struct** and **the typedef**
