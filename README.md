# python-utils

[![CI](https://github.com/damense/python-utils/actions/workflows/ci.yml/badge.svg)](https://github.com/damense/python-utils/actions/workflows/ci.yml)

Small utility functions, ported from R as I learn idiomatic Python.

## About

I'm an experienced R programmer (tidyverse, S4, Shiny, lme4) moving
towards Python for data science. This repo is a sandbox for porting
small utilities from R to Python, practising the modern toolchain, and
writing tests as I go.

Tooling: 
[uv](https://docs.astral.sh/uv/) for environment and package management, 
[ruff](https://docs.astral.sh/ruff/) for lint and format,
[pyright](https://microsoft.github.io/pyright/) for type checking,
[pytest](https://docs.pytest.org/) for tests. Type hints everywhere.

## What's here

- `tests/` — pytest suite
- `src/python_utils/` — the utilities themselves (currently scaffolding)

More will be added as I work through the 13-week Python programme.
