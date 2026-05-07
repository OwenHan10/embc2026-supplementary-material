# Supplementary Material for EMBC 2026 Paper

This repository contains supplementary cohort information and cross-validation split files for the EMBC 2026 paper:

**Single-Channel Respiratory-Effort Temporal Event Segmentation for Second-Level Central Sleep Apnea Detection**

## Overview

This supplementary material provides the subject IDs used in the study and the pre-computed subject-level five-fold cross-validation splits. These files are provided to improve transparency and reproducibility of the experimental design.

The study uses a balanced subject cohort constructed from the MrOS dataset. All selected subjects with central apnea index (CAI) greater than 5 are included as the CSA cohort. A matched non-CSA cohort with CAI less than or equal to 5 is selected at a 1:1 ratio based on age and body mass index (BMI), resulting in a total of 476 subjects.

## Repository Contents

```text
.
├── mros_csa.txt
├── mros_non_csa.txt
├── mros_cross_validation_splits.csv
└── README.md
