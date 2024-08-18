Methylation Analysis Pipeline Script :

This Bash script automates the process of methylation analysis, including quality control, trimming, genome indexing, alignment, and methylation extraction and reporting. The script is interactive and requires user input for various paths and parameters. Below is a detailed explanation of the script and its usage.

Features :

    Quality Control: Runs FASTQC for initial quality control of input files.
    Trimming: Trims adapters and low-quality bases using TrimGalore.
    Genome Indexing: Prepares the reference genome for alignment using Bismark.
    Alignment: Aligns the trimmed reads to the reference genome using Bismark, supporting both paired-end (PE) and single-end (SE) reads.
    Methylation Extraction: Extracts methylation information using Bismark's methylation extractor.
    Report Generation: Generates methylation reports for visualization and analysis.
