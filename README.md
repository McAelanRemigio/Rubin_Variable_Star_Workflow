# Rubin Variable Star Workflow Demo

This repository presents a minimal, end-to-end data analysis workflow
for identifying candidate variable stars. It is a standalone, personal
demonstration derived from methods used in a collaborative
Vera C. Rubin Observatory project.

The goal of this repository is to demonstrate how an exploratory,
research-oriented analysis can be distilled into a clear and
reproducible workflow.

---

## Workflow Overview

The analysis follows a simple, linear pipeline:

1. Load and inspect time-series data
2. Perform exploratory data analysis (EDA)
3. Compute variability metrics
4. Rank candidate variable stars
5. Generate diagnostic outputs

---

## Repository Structure

rubin-variable-star-workflow/
├── run_pipeline.ipynb # End-to-end workflow notebook
├── data/ # Input data (small sample)
├── outputs/ # Generated tables and plots
└── README.md


---

## Outputs

- **Ranked candidate table** (`outputs/ranked_candidates.csv`)
- **Diagnostic plot(s)** (`outputs/diagnostics.png`)

These outputs represent the terminal artifacts of the workflow.

---

## Scope & Limitations

This repository is intended as a workflow demonstration rather than a
complete scientific analysis. It does not include full astrophysical
validation or machine learning models.

In practice, ranked candidates produced by this workflow would be
passed to downstream classification or modeling stages.

---

## Attribution

This demo is informed by prior collaborative work conducted as part of
a Vera C. Rubin Observatory project. The full collaborative archive is
maintained separately.
