# scRNA-seq Analysis Project

A structured computational biology project for learning and applying Python, Scanpy, and single-cell RNA-seq analysis.

## Project Overview

This project demonstrates a reproducible single-cell RNA-seq analysis workflow using the PBMC3k dataset.

The first phase focuses on building practical skills in Python, AnnData, Scanpy, quality control, dimensionality reduction, clustering, marker-gene analysis, and cell-type annotation.

The project is designed as a skill-demonstration and portfolio project, rather than a novel biological discovery study.

## Phase 1 — PBMC3k

### Completed Workflow

Raw PBMC3k
→ Quality Control
→ Cell Filtering
→ Normalization
→ Log Transformation
→ Highly Variable Gene Selection
→ Scaling
→ PCA
→ Neighbors
→ UMAP
→ Leiden Clustering
→ Marker Gene Analysis
→ Cell-type Annotation

### Completed Lessons

- Lesson 01 — Python environment and variables
- Lesson 02 — Lists and dictionaries
- Lesson 03 — Loops and conditions
- Lesson 04 — Functions
- Lesson 05 — Objects and AnnData structure
- Lesson 06 — NumPy basics
- Lesson 07 — Pandas basics
- Lesson 08 — Matplotlib basics
- Lesson 09 — Quality control with Scanpy
- Lesson 10 — File paths, saving and loading AnnData
- Lesson 11 — Git and GitHub project setup
- Lesson 12 — Normalization, HVG selection, PCA and UMAP
- Lesson 13 — Leiden clustering and marker-gene analysis
- Lesson 14 — Cell-type annotation and PBMC3k pipeline finalization

## Cell-type Annotation

Cell identities were assigned based on Leiden clusters, ranked marker genes, and canonical marker-gene expression.

The final annotation includes:

- T cell
- Cytotoxic T / NK-like
- B cell
- NK cell
- Classical Monocyte
- Dendritic cell
- Platelet / Megakaryocyte

## Repository Structure

scRNA_project/
├── datasets/
├── notebooks/
├── .gitignore
├── requirements.txt
└── README.md

Large .h5ad files are kept locally in the datasets directory and excluded from Git tracking.

## Next Phase

The next stage of the project will apply the learned single-cell RNA-seq workflow to a real colorectal cancer dataset (GSE132465).

A separate R-based analysis track will also be developed for TCGA-COAD transcriptomics and statistical analysis.
