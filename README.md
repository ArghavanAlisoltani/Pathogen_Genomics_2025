# Pathogen_Genomics_2025

This repository accompanies the Pathogen Genomics 2025 course. It serves as a
collaborative space for exploring pathogen genomes and practicing
bioinformatics techniques for sequence analysis and interpretation.

For a step-by-step analysis workflow, see the [course wiki](WIKI.md).

## Prerequisites

Before starting, you'll need several command-line tools. We highly recommend installing them in a dedicated Conda environment.

1. **Install Conda/Miniconda**: If you don't have it, follow the instructions at the Conda installation guide.
2. **Create Conda Environment**:

```bash
conda create -n sars-cov2-analysis -c bioconda -c conda-forge fastqc trimmomatic bwa samtools bcftools ivar nextclade
```
3. **Activate the Environment**:

```bash
conda activate sars-cov-2-analysis
```
4. **Download Reference Data**: You'll need the SARS-CoV-2 reference genome (Wuhan-Hu-1) and a BED file defining the primer locations for your amplicon scheme (e.g., ARTIC v3/v4).
