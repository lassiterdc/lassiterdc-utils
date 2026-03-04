# Installation

## Create environment

```bash
conda create -n lassiterdc_utils python=3.11
conda activate lassiterdc_utils
```

## Install

```bash
pip install -e ".[docs]"
```

!!! note
    The `[docs]` extra installs MkDocs and mkdocstrings for building documentation locally.
    Omit it for a minimal install: `pip install -e .`
