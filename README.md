# PLncFire
A Scalable Pipeline for Transcriptome-wide Discovery of Plant lncRNAs

## Project Overview
The project PLncFire is a scalable and reproducible computational pipeline for genome-wide identification and annotation of plant long non-coding RNAs (lncRNAs) from RNA-seq data. The workflow integrates high-resolution transcriptome reconstruction with a consensus coding-potential evaluation framework that leverages CPC2, PlantLncPipe, and FEELnc, thereby enhancing the reliability of both known and novel lncRNA detection. In addition, PLncFire supports downstream differential expression analyses, enabling systematic investigation of lncRNA dynamics and potential regulatory roles across diverse plant species.

## Data Description
PLncFire processes high-throughput RNA-seq data (paired-end or single-end) generated from plant transcriptomes. The pipeline requires raw sequencing reads in FASTQ format and corresponding reference genome (FASTA) and gene annotation (GTF/GFF3) files. It supports data from both model and non-model plant species. Publicly available or user-generated RNA-seq datasets can be used for lncRNA discovery, annotation, and downstream differential expression analysis.

## Installation Prerequisites
Make sure you have following libraries installed.
* SRA Toolkit
* HISAT2
* StringTie
* LncFinder
* CPAT
* Diamond

## Usage
See Code Folder

## Contact
Dr Ahsan Z Rizvi, ahsan.rizvi@iar.ac.in
