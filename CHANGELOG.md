# CHANGELOG

Inspired from [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]

### Added

- Added CHANGELOG ([#309](https://github.com/opensearch-project/opensearch-api-specification/pull/309))
- Added a spec test framework ([#299](https://github.com/opensearch-project/opensearch-api-specification/pull/299))
- Added tests for the framework ([#310](https://github.com/opensearch-project/opensearch-api-specification/pull/310))
- Added workflow to determine API changes ([#297](https://github.com/opensearch-project/opensearch-api-specification/pull/297))
- Added link checking ([#269](https://github.com/opensearch-project/opensearch-api-specification/pull/269))
- Added API coverage ([#210](https://github.com/opensearch-project/opensearch-api-specification/pull/210))
- Added license headers to TypeScript code ([#311](https://github.com/opensearch-project/opensearch-api-specification/pull/311))
- Added `npm run test:spec -- --dry-run --verbose` ([#303](https://github.com/opensearch-project/opensearch-api-specification/pull/303))
- Added `npm run test:unit` and `test:integ` ([#320](https://github.com/opensearch-project/opensearch-api-specification/pull/320))
- Added code coverage to tools' tests ([#323](https://github.com/opensearch-project/opensearch-api-specification/pull/323))
- Added a YAML linter ([#312](https://github.com/opensearch-project/opensearch-api-specification/pull/312))
- Added linter to validate order of spec operations ([#325](https://github.com/opensearch-project/opensearch-api-specification/pull/326)) ([#326](https://github.com/opensearch-project/opensearch-api-specification/pull/326))
- Added support to read outputs from requests in tests([#324](https://github.com/opensearch-project/opensearch-api-specification/pull/324))
- Added `eslint-plugin-eslint-comments` ([#333](https://github.com/opensearch-project/opensearch-api-specification/pull/333))
- Added `distribution` field to `OpenSearchVersionInfo` ([#336](https://github.com/opensearch-project/opensearch-api-specification/pull/336)) 
- Added `created_time` and `last_updated_time` to `ml.get_model_group@200` ([#342](https://github.com/opensearch-project/opensearch-api-specification/pull/342))
- Added spellcheck linter ([#341](https://github.com/opensearch-project/opensearch-api-specification/pull/341))
- Added tests for response payload ([#347](https://github.com/opensearch-project/opensearch-api-specification/pull/347))
- Added `cancel_after_time_interval` and `phase_took` in `_search` ([#353](https://github.com/opensearch-project/opensearch-api-specification/pull/353))
- Added support for testing `application/x-ndjson` payloads ([#355](https://github.com/opensearch-project/opensearch-api-specification/pull/355))
- Added SPECIFICATION_TESTING.md [#359](https://github.com/opensearch-project/opensearch-api-specification/pull/359)
- Added StoryValidator to validate stories before running them ([#354](https://github.com/opensearch-project/opensearch-api-specification/issues/354))
- Added support for `text/plain` responses in `_cat` APIs ([#360](https://github.com/opensearch-project/opensearch-api-specification/pull/360))
- Added support for `application/yaml` responses ([#363](https://github.com/opensearch-project/opensearch-api-specification/pull/363))
- Added test for search with seq_no_primary_term ([#367](https://github.com/opensearch-project/opensearch-api-specification/pull/367))
- Added a linter for parameter sorting ([#369](https://github.com/opensearch-project/opensearch-api-specification/pull/369))
- Added support for `application/cbor` responses ([#371](https://github.com/opensearch-project/opensearch-api-specification/pull/371))
- Added support for `application/smile` responses ([#386](https://github.com/opensearch-project/opensearch-api-specification/pull/386))
 
### Changed

- Replaced Smithy with a native OpenAPI spec ([#189](https://github.com/opensearch-project/opensearch-api-specification/issues/189))
- Refactored spec tester internals to improve reusability ([#302](https://github.com/opensearch-project/opensearch-api-specification/pull/302))
- Renamed `main` release tag to `main-latest` ([#321](https://github.com/opensearch-project/opensearch-api-specification/pull/321))
- Replaced usages of `Opensearch` with `OpenSearch` ([#335](https://github.com/opensearch-project/opensearch-api-specification/pull/335))
- Prevented merger tool from printing warnings when used by tester tool [#359](https://github.com/opensearch-project/opensearch-api-specification/pull/359)
- Replaced the deprecated fs.rmdirSync with fs.rmSync [#359](https://github.com/opensearch-project/opensearch-api-specification/pull/359)
- Tester tool now provides better context for non-2XX responses when --verbose is used [#359](https://github.com/opensearch-project/opensearch-api-specification/pull/359)

### Deprecated

### Removed

- Removed the ability to skip an individual spec test ([#358](https://github.com/opensearch-project/opensearch-api-specification/pull/358)
 
### Fixed

- Fixed GitHub pages ([#215](https://github.com/opensearch-project/opensearch-api-specification/pull/215))
- Fixed missing 201 response in `/{index}/_doc/{id}` ([#331](https://github.com/opensearch-project/opensearch-api-specification/pull/331))
- Fixed `SlowlogThresholds` ([#341](https://github.com/opensearch-project/opensearch-api-specification/pull/341))
- Fixed `from_address` in `SmtpAccount` ([#341](https://github.com/opensearch-project/opensearch-api-specification/pull/341))
- Fixed `pages_processed` in `/_plugins/_rollup` ([#341](https://github.com/opensearch-project/opensearch-api-specification/pull/341))
- Fixed `_bulk` spec request and response types ([#355](https://github.com/opensearch-project/opensearch-api-specification/pull/355))
- Fixed `text/plain` response in `/_cat` ([#357](https://github.com/opensearch-project/opensearch-api-specification/pull/357))
- Fixed `/_cat/cluster_manager`, `/_cat/allocation`, `/_cat/shards`, and `/_cat/thread_pool` ([#373](https://github.com/opensearch-project/opensearch-api-specification/pull/373))
- Fixed optional field in `/_nodes` ([#365](https://github.com/opensearch-project/opensearch-api-specification/pull/365))
- Fixed `/{index}/_open` can return a `task` ([#376](https://github.com/opensearch-project/opensearch-api-specification/pull/376))
- Fixed `_source` in `bulk` responses ([#375](https://github.com/opensearch-project/opensearch-api-specification/pull/375))
- Fixed `/{index}/_dangling` that can return `nodes` and `cluster_name` ([#391](https://github.com/opensearch-project/opensearch-api-specification/pull/391))

### Security

[Unreleased]: https://github.com/opensearch-project/opensearch-api-specification/commits/main/
