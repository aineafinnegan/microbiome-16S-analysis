# Pouchitis Microbiome Analysis - 16S rRNA Sequencing

Microbiome profiling of gut samples from pouchitis patients using 16S rRNA sequencing and the DADA2 pipeline.

## Overview
- **Study**: Longitudinal microbiome analysis in pouchitis patients
- **Sample types**: Ileum, pouch, and rectum biopsies across multiple timepoints
- **Methods**: DADA2 pipeline for sequence processing, phyloseq for ecological analysis
- **Patients**: 5 patients (2 with pouchitis, 3 without)

## Key Analyses
- Quality filtering and error modeling
- Taxonomic assignment using Silva database
- Alpha diversity (Shannon, Simpson indices)
- Beta diversity (Bray-Curtis, weighted/unweighted UniFrac)
- Taxonomic composition at phylum, family, and genus levels

## Key Findings
- Distinct microbial communities between biopsy sites
- Pouchitis patients show altered diversity patterns
- Site-specific bacterial composition differences

## Requirements
- R (≥4.0)
- dada2
- phyloseq
- ggplot2
- ape
