# Methodology

## Overview

This project presents an in silico analysis of selected amino-acid variants of the human PTEN protein. Multiple computational prediction tools and publicly available clinical databases were used to investigate the potential functional, structural, stability-related, and clinical significance of the selected variants.

## Reference Protein

The canonical human PTEN protein was used as the reference sequence.

- **Gene:** PTEN (Phosphatase and Tensin Homolog)
- **Organism:** Homo sapiens
- **NCBI Gene ID:** 5728
- **Canonical transcript:** NM_000314.8
- **Canonical protein:** NP_000305.3
- **Protein length:** 403 amino acids
- **UniProt accession:** P60484

The canonical PTEN protein contains the N-terminal phosphatase domain followed by the C2 domain and C-terminal regulatory region.

## Variant Panel

Ten selected PTEN amino-acid substitutions were investigated:

1. C124S
2. C124G
3. C124Y
4. C124W
5. R130G
6. R130L
7. R130P
8. P204A
9. G251V
10. T277R

## Computational Analysis

### 1. SIFT

SIFT was used to predict whether individual amino-acid substitutions are likely to affect protein function.

The SIFT prediction and score obtained for each selected variant were recorded in the integrated dataset.

### 2. PolyPhen-2

PolyPhen-2 was used as an additional computational predictor of the potential functional and structural impact of the selected amino-acid substitutions.

The prediction category and score were recorded for each available variant result.

### 3. I-Mutant 2.0

I-Mutant 2.0 was used to estimate the effect of amino-acid substitutions on protein stability.

The predicted change in Gibbs free energy (ΔΔG) and corresponding stability prediction were recorded.

A negative ΔΔG value was interpreted by the tool as a predicted decrease in protein stability, whereas a positive value was interpreted as a predicted increase in stability.

### 4. Project HOPE

Project HOPE was used to investigate the structural and physicochemical consequences of the selected substitutions.

The analysis considered changes such as:

- Amino-acid residue size
- Hydrophobicity
- Charge
- Hydrogen-bonding interactions
- Local structural environment
- Potential effects on protein folding and stability
- Conservation of the affected residue

The HOPE results were used as supporting structural evidence rather than as experimental proof of functional effects.

### 5. ClinVar

ClinVar was used to obtain available clinical annotations for the selected PTEN variants.

Clinical significance classifications and associated information were incorporated into the integrated variant dataset where available.

## Integrated Interpretation

The results from SIFT, PolyPhen-2, I-Mutant 2.0, Project HOPE, and ClinVar were considered together to provide a comparative assessment of the selected PTEN variants.

Individual computational predictions were not treated as definitive experimental evidence. Where different prediction tools produced different outcomes, the disagreement was retained and considered during interpretation.

## Data Organization

The repository contains the integrated variant dataset in two formats:

- `data/PTEN_variant_analysis.xlsx` — master Excel dataset
- `data/PTEN_variant_analysis.csv` — machine-readable dataset

The dataset contains the recorded computational predictions, stability results, structural interpretations, and clinical annotations for the ten selected PTEN variants.

## Limitations

This study is based primarily on computational predictions and publicly available database annotations. Computational predictions indicate possible effects but do not establish experimental molecular mechanisms or clinical causality.

Experimental validation would be required to confirm the effects of individual PTEN variants on protein structure, stability, enzymatic activity, cellular function, or disease phenotype.

## Reproducibility

The recorded results and integrated dataset are provided in this repository to facilitate transparency and reproducibility of the computational analysis.
