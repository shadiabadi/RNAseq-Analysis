# RNAseq-Analysis

## Overview
This project provides an End-to-end RNA-seq analysis from raw FASTQ files to differential expression and pathway enrichment analysis using DESeq2 and GSEA.

## Workflow Steps
1. **Preprocessing**: Quality control and read trimming
2. **Read Alignment**: Alignment using STAR or HISAT2
3. **Quantification**: Counting reads per gene
4. **Differential Expression Analysis**: Using DESeq2
5. **Gene Set Enrichment Analysis (GSEA)**: Pathway analysis

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/shadiabadi/RNAseq-Analysis
   cd RNAseq-Analysis

2. Create the Conda environment:
   conda env create -f environment.yml
   conda activate rnaseq-env

3. Run the pipeline:
   bash scripts/run_pipeline.sh
