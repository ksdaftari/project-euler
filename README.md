[![uv](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/uv/main/assets/badge/v0.json)](https://github.com/astral-sh/uv)

# project-euler
attempting to answer [Project Euler](https://projecteuler.net) questions using different programming languages

## Install

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

if above doesn't work, follow [`uv` installation](https://docs.astral.sh/uv/getting-started/installation/#installation-methods)

> [!NOTE]
> With [`uv`](https://docs.astral.sh/uv/), no python or other pre-reqs needed. the simple `uv run` command will install python and package depdencis automatically prior to running any script

## Run answer

To run script for answer use command below

```bash
uv run scripts/<number>/main.py
```

so for [001](https://projecteuler.net/problem=1)

```bash
uv run scripts/001/main.py
```