# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.5.1](https://github.com/antonbaliasnikov/era-compiler-common/releases/tag/v{version}) - 2024-11-22

### Other

- release v1.5.0

## [1.5.0](https://github.com/antonbaliasnikov/era-compiler-common/releases/tag/era-compiler-common-fork-v1.5.0) - 2024-11-22

### Added

- add EVM version `prague` ([#23](https://github.com/antonbaliasnikov/era-compiler-common/pull/23))
- add the contract name representation
- CBOR endpoint for IPFS hash

### Fixed

- add release plz
- downloading on Windows via compiler bin JSON ([#24](https://github.com/antonbaliasnikov/era-compiler-common/pull/24))
- set full semver for dependencies ([#22](https://github.com/antonbaliasnikov/era-compiler-common/pull/22))
- the CBOR header
- serde arrays

### Other

- move contract code segment to this crate ([#25](https://github.com/antonbaliasnikov/era-compiler-common/pull/25))
- add cross dependency testing workflow ([#20](https://github.com/antonbaliasnikov/era-compiler-common/pull/20))
- renaming to era-compiler-downloader and era-compiler-common ([#19](https://github.com/antonbaliasnikov/era-compiler-common/pull/19))
