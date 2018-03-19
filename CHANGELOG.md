# Changelog

All notable changes to FlakeLedger are documented in this file.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Changed

- Rule tables are being reorganised for the next patch.

## [1.0.1] - 2026-07-21

### Fixed

- Runs sharing a timestamp are ordered by file name so the classification is
  stable across machines.
- A fixture for the tie, and the smoke run now covers it.

## [1.0.0] - 2026-02-10

### Added

- Stable CLI contract: `classify`, `cost` and `report` with exit codes 0, 1
  and 2.
- `docs/FORMAT.md` as the written contract for the JUnit input and the report.
- Deterministic JSON report with a fixed key order.

## [0.9.0] - 2025-03-25

### Added

- Quarantine suggestions with the evidence runs that support them.
- `--min-runs` so a single failing run never earns the flaky label.

## [0.7.0] - 2024-06-18

