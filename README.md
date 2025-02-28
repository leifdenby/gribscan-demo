# `gribscan` demo for United Weather Centers (UWC) - 2025-02-28

This repository contains the python environment and notebooks used to demonstrate the `gribscan` package for United Weather Centers (UWC) on 2025-02-28.

The main notebook is the one demonstrating working with [UWC-W DINI Harmonie forecast data](notebooks/uwcw-dini-lcd.ipynb).

## Installation

If you haven't already got python installed, I heavily recommend installing the fast and lightweight `uv` package manager:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

You can then install the dependencies for this project using the following command:

```bash
uv sync
```

This will create a virtual environment in `.venv/` that you can activate if you wish to run the gribscan commands outside of the repository:

```bash
source .venv/bin/activate
```