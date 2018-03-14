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
