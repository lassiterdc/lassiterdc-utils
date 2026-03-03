# Installation

## Create environment

```bash
conda create -n dcl_utils python=3.11
conda activate dcl_utils
```

## Install

```bash
pip install -e ".[docs]"
```

!!! note
    The `[docs]` extra installs MkDocs and mkdocstrings for building documentation locally.
    Omit it for a minimal install: `pip install -e .`
