# Adult PBPK Model Development & Validation

## Overview
Develop and validate adult PBPK models as a foundation for pediatric extrapolation and EMA-aligned PBPK qualification.

## Objective
Build adult PBPK models for Voriconazole, Levetiracetam, Clopidogrel, and Etanercept using in vitro and clinical PK data.

## Tools
- PK-Sim (GUI-based PBPK modeling)
- mrgsolve (R) for reproducible simulations
- Python/R for plotting and validation metrics

## Innovation / Twists
- Cross-platform validation (PK-Sim vs mrgsolve)
- Consideration of **formulation differences** (oral vs IV)
- Sensitivity analysis for key PK parameters

## Deliverables
- `/pk-sim/adult_models/*.pksim5`
- `/mrgsolve/adult_models/*.R` scripts
- `/analysis/validation_plots.ipynb` with Predicted vs Observed plots, AFE, % within 2-fold

## EMA Alignment
Supports **Stage 2.1**: adult PBPK model development and validation.
