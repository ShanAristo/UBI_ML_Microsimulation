# UBI Dissertation — Supplementary Materials

This repository hosts supplementary artefacts for my dissertation:
“Modelling Universal Basic Income with Microsimulation and Interpretable ML”.

## What’s here

- `notebook/` — end-to-end analysis notebook (microsimulation + ML).
- `diagnostics/` — data quality and exploratory outputs
- `descriptive_outputs/` — shareable descriptive statistics and aggregated summaries
- `simulation_outputs/` — policy scenario outputs (decile uplifts, summaries).
- `models/` — classification artefacts (confusion matrices, ROC, coefficients).
- `tables/` — supporting tables, including variable code–label mappings
- `env/` — environment files for reproducibility (Python versions & packages).

> **Note**: Note: Licensed microdata (LCFS) is **not** included. Only non-disclosive outputs (aggregated summaries and descriptive statistics) appear here.

## Appendix cross-reference

- **Appendix A →** `notebook/`, `env/`, top-level `requirements.txt`
- **Appendix B →** `tables/`  *(variable map & code–label mappings)*
- **Appendix C →** `tables/`  *(expanded code–label mappings)*
- **Appendix D →** `data_previews/`  *(additional categorical distributions, etc.)*
- **Appendix E →** `diagnostics/`  *(missingness heatmaps )*



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
