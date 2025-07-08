# R scripts for the analysis of depression and anxiety after cancer diagnosis

This repository contains R scripts used in a study investigating the incidence of depression and anxiety disorders following cancer diagnosis. The analysis was conducted using municipal-level healthcare claims data.

## Environment

- R version: 4.2.1
- Key packages: `tidyverse`, `survival`, `survey`, `splines`, etc.

## File structure

### 📊 Main analyses
- `Analysis_depression.Rmd`: Main analysis of depression incidence after cancer diagnosis.
- `Analysis_anxiety.Rmd`: Main analysis of anxiety disorder incidence after cancer diagnosis.

### 🔍 Subgroup and related analyses
- `Analysis_subtype.Rmd`: Subgroup analysis by cancer type.
- `Analysis_examination.Rmd`: Analysis of the association between medical examinations and mental health outcomes.

### 📐 Sensitivity analyses
- `Sensitivity_analysis_depression.Rmd`: Sensitivity analysis for depression.
- `Sensitivity_analysis_anxiety.Rmd`: Sensitivity analysis for anxiety disorders.

## Notes

- The preprocessing code cannot be made publicly available due to privacy concerns.
- The actual analysis scripts have been modified to anonymise municipality-specific variables and identifiers in accordance with data use agreements and privacy regulations.
- Patient-level data are not included in this repository.

## Contact

For further information, please contact the corresponding author of the study.
