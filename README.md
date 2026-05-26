# Transcriptomic Analysis of EZH2 Inhibitor-Treated E2 Glioblastoma Stem Cells
## Overview
This repository contains an ongoing computational oncology project investigating transcriptomic responses to EZH2 inhibition in E2 glioblastoma stem cells.
The project focuses on identifying differential gene expression patterns and biologically relevant pathways altered following epigenetic inhibitor treatment.
## Background
Glioblastoma (GBM) is an aggressive and treatment-resistant primary brain tumour characterized by high intratumoral heterogeneity and stem-like cellular populations. EZH2, a catalytic component of the Polycomb Repressive Complex 2 (PRC2), regulates transcriptional repression through histone methylation and has been implicated in glioblastoma stemness, proliferation, and therapeutic resistance. This project investigates transcriptomic alterations induced by EZH2 inhibitor treatment in E2 glioblastoma stem cells.
## Objectives
- Investigate transcriptomic responses to EZH2 inhibition
- Identify differentially expressed genes (DEGs)
- Evaluate pathways associated with proliferation, stemness, and chromatin remodeling
- Explore epigenetic mechanisms involved in glioblastoma progression
## Dataset Information
Cell Line:
- E2 glioblastoma stem cells
Treatment Conditions:
- EPZ6438
- UNC1999
- GSK343
Data Source:
- Publicly available RNA-seq datasets from GEO/SRA
## Computational Workflow
FASTQC -> HISAT2 (Read Alignment) -> Infer Experiment -> StringTie (Transcript Assembly) -> DESeq2 (Differential Expression Analysis) -> Gene Ontology and Pathway Enrichment -> Biological Interpretation
## Tools and Platforms
- Galaxy Europe
- HISAT2
- StringTie
- DESeq2
- Excel
- ToppGene
## Current Status
Ongoing Computational Oncology Project

Expected Completion : July 2026

Current Progress:
- FASTQ acquisition completed
- Quality control in progress
- Alignment and transcript quantification ongoing
- Differential expression analysis pending
## Key Biological Themes
- EZH2-mediated epigenetic regulation
- Glioblastoma stemness
- Chromatin remodeling
- Cell proliferation
- Therapeutic response pathways
## Future Directions
- Comparative analysis with additional GBM datasets
- Integration with pathway-specific analyses
- Translational interpretation of epigenetic inhibitor responses
## Author
Sriprata Ramasubramanian
MSc.Medical Genetics & Genomics 
