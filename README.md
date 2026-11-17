# Diploma Thesis Project

This repository contains the code, research materials, documentation, and results for the diploma thesis.

## Repository structure

- `data/raw/` — original, unmodified input data (do not commit large or restricted datasets).
- `data/processed/` — derived and preprocessed data.
- `docs/` — thesis text, methodology, project description, references, and figures.
- `notebooks/` — exploratory and analysis notebooks.
- `results/` — generated tables, figures, and analysis outputs.
- `src/` — reusable source code.
- `tests/` — tests for reusable code.

## Current analysis

The notebook in `notebooks/Untitled16.ipynb` contains the current neuroimaging workflow, including OpenNeuro dataset inspection, BOLD/T1w image inspection, atlas-based ROI extraction, and functional-connectivity analysis.

## Getting started

1. Review `requirements.txt` and install the dependencies.
2. Place permitted source data under `data/raw/` and derived data under `data/processed/`.
3. Open the notebook in `notebooks/` and update any data paths to match the local environment.
4. Save generated figures and tables under `results/`.

See `docs/project_description.md` and `docs/methodology.md` for documentation entry points.
