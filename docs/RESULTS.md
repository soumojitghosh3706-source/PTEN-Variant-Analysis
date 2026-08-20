# Results

## Overview

The integrated analysis evaluated ten selected amino-acid substitutions in the human PTEN protein using SIFT, PolyPhen-2, I-Mutant 2.0, Project HOPE, and ClinVar. The results below are transcribed from the final `PTEN_variant_analysis.xlsx` dataset.

## 1. Summary of the 10 Variants

| Variant | Domain | SIFT | PolyPhen-2 | I-Mutant ΔΔG (kcal/mol) | Stability | Overall interpretation |
|---|---|---|---|---:|---|---|
| C124S | Catalytic / phosphatase | Affect protein function (0) | Probably damaging (1) | -0.49 | Decreased | Strongly damaging |
| C124G | Catalytic / phosphatase | Affect protein function (0) | Probably damaging (1) | -1.21 | Decreased | Strongly damaging |
| C124Y | Catalytic / phosphatase | Affect protein function (0.01) | Probably damaging (1) | -0.45 | Decreased | Damaging |
| C124W | Catalytic / phosphatase | Affect protein function (0) | Probably damaging (1) | -0.45 | Decreased | Strongly damaging |
| R130G | Catalytic / phosphatase | Affect protein function (0.03) | Probably damaging (1) | -0.45 | Decreased | Strongly damaging |
| R130L | Catalytic / phosphatase | Affect protein function (0.04) | Probably damaging (1) | 0.07 | Increased | Functionally damaging despite minimal stability change |
| R130P | Catalytic / phosphatase | Affect protein function (0.03) | Probably damaging (1) | -0.46 | Decreased | Strongly damaging |
| P204A | C2 | Tolerated (0.12) | Probably damaging (0.998) | 0.1 | Increased | Discordant functional/stability prediction |
| G251V | C2 | Affect protein function (0) | Probably damaging (0.999) | -1.19 | Decreased | Strongly damaging |
| T277R | C2 | Affect protein function (0) | Probably damaging (1) | 0.41 | Increased | Functionally damaging despite increased stability |

## 2. Functional Prediction

SIFT predicted that **9 of the 10 variants** would affect protein function. The exception was **P204A**, which was classified as tolerated with a SIFT score of 0.12.

The lowest SIFT scores in the dataset were observed for C124S, C124G, C124W, G251V and T277R (score 0), indicating strong predicted functional impact according to SIFT.

## 3. PolyPhen-2 Prediction

PolyPhen-2 classified **all ten variants as probably damaging**.

The scores were 1.000 for most variants, while P204A had a score of 0.998. Thus, PolyPhen-2 provided a highly consistent prediction of potential functional/structural damage across the selected variant panel.

## 4. Protein Stability Prediction

I-Mutant 2.0 predicted decreased stability for seven variants and increased stability for three variants.

### Predicted decrease in stability

- C124S: **−0.49 kcal/mol**
- C124G: **−1.21 kcal/mol**
- C124Y: **−0.45 kcal/mol**
- C124W: **−0.45 kcal/mol**
- R130G: **−0.45 kcal/mol**
- R130P: **−0.46 kcal/mol**
- G251V: **−1.19 kcal/mol**

The largest predicted decreases were observed for **C124G** and **G251V**.

### Predicted increase in stability

- R130L: **+0.07 kcal/mol**
- P204A: **+0.10 kcal/mol**
- T277R: **+0.41 kcal/mol**

These results show that an increase in predicted stability does not necessarily correspond to a benign functional prediction.

## 5. Project HOPE Structural and Functional Findings

The HOPE analysis identified several recurring structural features.

### C124 substitutions

C124 is located in the catalytic/phosphatase domain and is described in the dataset as an active-site residue. The residue is reported as 100% conserved in the analysed sequences.

- **C124S:** altered hydrophobicity and predicted disruption of the wild-type hydrogen bond with Thr131.
- **C124G:** smaller and less hydrophobic residue, with predicted loss of hydrophobic interactions, loss of the Thr131 hydrogen bond, and increased local flexibility.
- **C124Y:** larger and less hydrophobic residue, with predicted poor fit in the buried core and loss of the Thr131 hydrogen bond.
- **C124W:** larger residue with predicted poor fit in the buried core, loss of hydrophobic interactions, and disruption of the Thr131 hydrogen bond.

### R130 substitutions

R130 is located in the phosphatase tensin-type domain and is reported as 100% conserved.

- **R130G:** removes the positive charge and is predicted to disrupt a hydrogen bond with Phe90 and salt bridges involving Glu73, Glu91 and Asp92.
- **R130L:** removes the positive charge and is predicted to disrupt the same hydrogen bond and salt-bridge interactions. Despite an I-Mutant prediction of increased stability, the integrated interpretation is functionally damaging.
- **R130P:** removes the positive charge and is predicted to disrupt the hydrogen bond with Phe90 and the salt bridges involving Glu73, Glu91 and Asp92.

### C2-domain variants

- **P204A:** Ala is smaller than Pro. HOPE predicts an empty space in the protein core and possible disturbance of local conformation because Pro can impose a rigid backbone conformation.
- **G251V:** Val is larger and more hydrophobic than Gly. HOPE indicates that replacement of the highly flexible Gly residue may disturb the local structure.
- **T277R:** Arg is larger and positively charged compared with Thr. HOPE predicts possible folding problems, poor fit in the core, introduction of charge into a buried position, and loss of hydrophobic interactions.

## 6. ClinVar Annotations

All ten variants in the integrated dataset have ClinVar variation identifiers and clinical classification information.

The dataset reports:

- **Pathogenic:** C124G, R130G, R130P, P204A
- **Likely pathogenic:** C124S, G251V, T277R
- **Pathogenic/Likely pathogenic:** C124Y, C124W, R130L

The ClinVar review status varies between expert-panel reviewed records and records with criteria provided by multiple submitters without conflicts, as recorded in the master dataset.

## 7. Integrated Interpretation

The combined computational and clinical evidence indicates a strong overall damaging pattern across the selected PTEN variant panel.

Nine variants received an **Affect protein function** prediction from SIFT, while P204A was the only SIFT-tolerated variant. PolyPhen-2 classified all ten variants as probably damaging. I-Mutant predicted decreased stability for seven variants and increased stability for three.

Importantly, the stability prediction did not always track with functional prediction. **R130L, P204A, and T277R** were predicted by I-Mutant to increase stability, yet their other evidence indicates potential functional consequences. This illustrates why protein stability alone should not be used to classify a variant.

The most consistently damaging pattern is observed for variants affecting the conserved phosphatase-domain residues **C124 and R130**, where SIFT, PolyPhen-2, I-Mutant, Project HOPE and ClinVar annotations collectively support functional significance.

The C2-domain variants also show evidence of potential structural or functional disruption, particularly G251V and T277R.

## 8. Key Findings

1. **PolyPhen-2 predicted all ten variants to be probably damaging.**
2. **SIFT predicted nine variants to affect protein function.**
3. **Seven variants showed predicted decreased protein stability in I-Mutant.**
4. **C124G and G251V showed the largest predicted decreases in stability.**
5. **C124 and R130 substitutions occur in the phosphatase domain and affect highly conserved residues.**
6. **P204A showed discordant evidence:** SIFT predicted tolerance, while PolyPhen-2 predicted probable damage and ClinVar classified it as pathogenic.
7. **R130L and T277R demonstrate that increased predicted stability does not exclude functional damage.**
8. The ClinVar annotations in the master dataset classify all ten selected variants within pathogenic or likely-pathogenic categories.

## 9. Limitations

These findings represent an **in silico analysis** based on computational predictions and database annotations. They do not constitute experimental confirmation of altered PTEN enzymatic activity, protein folding, cellular localization, or disease mechanism.

Prediction-tool disagreement should be retained when interpreting individual variants. Experimental studies would be required to establish the molecular consequences of each substitution.

## 10. Data Source

The complete numerical results, ClinVar annotations, structural interpretations, and source notes are available in:

`data/PTEN_variant_analysis.xlsx`

A machine-readable version is available as:

`data/PTEN_variant_analysis.csv`
