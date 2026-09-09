# FromWetLabToR

Reproducible R workflows for quantitative analysis of wet-lab data.

## About

Molecular biologist working at the bench and in R. This repository
holds the analysis pipelines I build for my own experimental data —
scripted, version-controlled and reproducible, rather than done by
hand in spreadsheets.

## Projects

### Dose–response analysis of protein expression

End-to-end pipeline for quantitative densitometry data from a
6-point dose–response experiment across 4 biological replicates:

- Loading-control normalisation across independently run gels
- Expression relative to untreated control, log2-transformed
- Dunnett's test for multiple treatment groups against a single
  shared control
- Faceted dose–response figures with per-replicate points shown
  alongside group means

*Status: in progress*

## Note on data

The datasets in this repository are simulated. They match the
structure of real experimental data but contain no unpublished
results.

## Tools

R, dplyr, tidyr, ggplot2
