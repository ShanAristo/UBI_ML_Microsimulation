# UBI Dissertation — Supplementary Materials

This repository hosts supplementary artefacts for my dissertation:
“Modelling Universal Basic Income with Microsimulation and Interpretable ML”.

## What’s here

- `notebook/` — end-to-end analysis notebook (microsimulation + ML).
- `diagnostics/` — missingness heatmaps and top-20 NA plots (Appendix A).
- `data_previews/` — shareable excerpts of processed datasets (Appendix F).
- `simulation_outputs/` — policy scenario outputs (decile uplifts, summaries).
- `models/` — classification artefacts (confusion matrices, ROC, coefficients).
- `tables_tex/` — small LaTeX table excerpts used in the PDF appendices.
- `env/` — environment files for reproducibility (Python versions & packages).

> **Note**: Licensed microdata (LCFS) is **not** included. Only derived summaries/previews appear here.

## Appendix cross-reference

- Appendix A → `diagnostics/`
- Appendix B → distributions/correlations in `diagnostics/` and `data_previews/`
- Appendix D → `simulation_outputs/`
- Appendix E → `tables_tex/`, `env/`, plus selected CSVs in `data_previews/`
- Appendix F → `data_previews/`

## Reproducing results

1. Create a Python environment from `env/requirements.txt` (or `env/environment.yml`).
2. Open `notebook/UBI_Notebook.ipynb`.
3. Provide access to licensed LCFS data (paths documented in the notebook); run cells in order.
4. Outputs will be saved under `diagnostics/`, `models/`, and `simulation_outputs/`.

## Versioning

The submission snapshot is tagged `v1.0-submission`.


Two environment files are provided:

requirements.txt (full environment dump for exact reproducibility).

requirements_minimal.txt (core dependencies required to rerun the analysis).
