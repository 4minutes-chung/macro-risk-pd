# Macroeconomic Mortgage Credit Risk Modeling

This repository contains the final work of a group project by
**[Steven Chung](https://github.com/4minutes-chung)** and
**[Minh Thai Duong](https://github.com/MarshallianDemand)**. The project links
forward-looking macroeconomic scenarios to mortgage probability of default and
illustrative lifetime expected credit loss projections.

## Project Team

- **[Steven Chung](https://github.com/4minutes-chung)** developed the
  macroeconomic scenario model used to generate baseline, mild-recession, and
  severe-stress paths and was involved in macro-variable selection.
- **[Minh Thai Duong](https://github.com/MarshallianDemand)** developed the
  loan-level PD model, the final macro-variable selection workflow, and the
  lifetime PD projection.

## Final Report

[Read the final project report](write_up.pdf).

## Project Files

The repository keeps the filenames from the shared final project folder.

Suggested reading and execution order:

1. `Data Sampling.ipynb`
2. `Macro_clean_v2 (2).ipynb`
3. `Data_Analysis_clean.ipynb`
4. `Model_Development_clean.ipynb`
5. `Macro_Model_v2 (2).ipynb`
6. `PD_Projection (3).ipynb`

Supporting files:

- `macro_panel_quarterly.csv`
- `scenarios.csv`
- `sampling_stats.json`
- `bvar_results.pkl`
- `Macro_Model_v22_0_78815900_1777425903.pdf`

## Data

The following large local data files are not included in the public repository:

- `full_panel.parquet`
- `hazard_panel_full.parquet`
- `2025Q3.csv`

The notebooks are provided as project artifacts. A complete rerun requires the
excluded source data and the model-parameter handoff expected by the projection
notebook.

## Related Macro Engine

The separate macro forecast and scenario engine is available at
[macro-risk-v4](https://github.com/4minutes-chung/macro-risk-v4).
