# MASS_HTG

This repository contains code for investigating how circulating triglycerides relate to immune phenotypes and whole-blood transcriptional programmes during severe infection, with pathway analyses in MASS and cross-cohort comparisons in CMAISE.

## Analysis scripts

- [Analysis.Rmd](Analysis.Rmd) matches samples, preprocesses expression data, and calculates GSVA scores for GO Biological Process pathways in the MASS cohort. It evaluates associations of triglycerides with pathway activity and of pathway activity with immune phenotypes, with age-stratum interaction tests and sensitivity analyses. Multiple comparisons are adjusted using the Benjamini–Hochberg method.
- [leading_edge.Rmd](leading_edge.Rmd) uses differential expression and GSEA results comparing HTG with non-HTG in participants aged ≥65 years from the MASS and CMAISE cohorts. It selects pathways, matches gene identifiers, defines the shared analysis universe, and quantifies overlap between leading-edge gene sets.

