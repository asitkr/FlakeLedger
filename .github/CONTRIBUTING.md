# Contributing to FlakeLedger

Thanks for considering a contribution. FlakeLedger is an offline analyzer: it
reads JUnit XML files and never talks to a CI system.

## Development setup

- Python 3.11+. The package uses the standard library only.

```bash
python -m compileall -q src
python -m pytest -q
PYTHONPATH=src python -m flakeledger --help
```

## Before you open a pull request

1. Compile and the full test suite must pass.
2. Every new rule needs a fixture run set, a test and a paragraph in the README
   explaining the classification it produces.
3. Keep the package dependency-free.
