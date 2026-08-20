# PTEN Variant Analysis

## Overview

This repository contains an **in silico analysis of selected human PTEN protein variants** using multiple publicly available computational resources.

The analysis focuses on the predicted functional and structural consequences of ten selected amino-acid substitutions in the human PTEN protein.

## Variants analysed

- C124S
- C124G
- C124Y
- C124W
- R130G
- R130L
- R130P
- P204A
- G251V
- T277R

## Analysis workflow

The variant panel was evaluated using:

1. **SIFT** — prediction of potential effects on protein function.
2. **PolyPhen-2** — prediction of possible effects on protein structure/function.
3. **I-Mutant 2.0** — prediction of changes in protein stability (ΔΔG).
4. **Project HOPE** — structural and physicochemical interpretation of amino-acid substitutions.
5. **ClinVar** — clinical-variant information where available.

## Dataset

The complete integrated dataset is provided in:

- `data/PTEN_variant_analysis.xlsx` — master Excel dataset.
- `data/PTEN_variant_analysis.csv` — machine-readable version.

The Excel workbook contains the integrated prediction and annotation fields together with source/verification notes.

## I-Mutant stability results

| Variant | ΔΔG (kcal/mol) | Predicted stability |
|---|---:|---|
| C124S | -0.49 | Decreased |
| C124G | -1.21 | Decreased |
| C124Y | -0.45 | Decreased |
| C124W | -0.45 | Decreased |
| R130G | -0.45 | Decreased |
| R130L | +0.07 | Increased |
| R130P | -0.46 | Decreased |
| P204A | +0.10 | Increased |
| G251V | -1.19 | Decreased |
| T277R | +0.41 | Increased |

## Important scope note

This is an **in silico computational analysis**. Predictions from individual tools should not be interpreted as experimental proof of pathogenicity or molecular mechanism. Where different predictors disagree, the disagreement is retained in the dataset rather than being treated as experimental evidence.

## Reproducibility

The repository is intended to document the computational analysis and preserve the resulting dataset. Source databases/tools should be cited according to their respective usage and publication requirements when this work is presented academically.

## Author

**Soumojit Ghosh**

Undergraduate Biotechnology Student
