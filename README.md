# Satellite project
Scripts and code used for the Satellite project
The Satellite project samples include oral, gastric aspirates, duodenal aspirates and stools from stunted and non-stunted children age 2-5 years, from Bangui, Central African Republic.
DNA extraction was done with either promega or qiagen kit. Extracted DNA was send for shotgun metagenomic sequencing 12Gb at Novogene.

Samples:
    - Oral: 39
    - Gastric: 31
    - Duodenum: 14
    - Stool: 44

Published as preprint: https://doi.org/10.1101/2025.11.11.687814

## Published in Gut Microbes: https://doi.org/10.1080/19490976.2026.2653550

Data availability: Raw microbial metagenomic data, dereplicated (>98% ANI) Metagenome Assembled Genomes (MAGs, traceable by sample ID and MAG number, Supplementary Table S4) generated from this study and sequenced genomes from isolates (traceable by strain ID, Supplementary Table S2) have been deposited in the European Nucleotide Archives (ENA) at EMBL-EBI under accession number PRJEB102291.

## How to - Folders

### envs
> Conda environment installed on the HPC cluster from the UNIL to process metagenomic sequencing data and sequenced bacterial isolate genomes.

### scripts
> Bash scripts used on the HPC cluster to processes and analyze the data from the Satellite project.

### R_analysis_scripts
> This folder includes all scripts used for the analysis of the Satellite data.
