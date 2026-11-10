# PNG Rodent Gut Microbiome Analysis

## Description
This repository contains R scripts for analyzing the gut microbiome of murine rodents from Papua New Guinea (PNG). The workflow covers 16S rRNA gene profiling, functional metagenome predictions using PICRUSt2, and comparative analysis with published global rodent microbiome datasets.

## Repository Structure

```text
.
├── 01_16S_analysis.Rmd             # Analysis of 16S rRNA gene amplicon data
├── 02_picrust_predictions.Rmd      # Statistical analysis of predicted metagenomic pathways (PICRUSt2)
├── 03_PNG_vs_Youngblut.Rmd         # Comparative analysis of PNG rodents vs. Youngblut et al. (https://doi.org/10.1038/s41467-019-10191-3) dataset
├── data/
│   ├── Joined_scaled_RH85_corrected.nwk # ddRAD host phylogenetic tree used in analyses
│   ├── PHS.mam.sp.fam.Rdata         # Reanalyzed data from Youngblut et al. (2019)
│   ├── PHS.pic_path_v2.RData        # Processed data object containing predicted metagenome pathways
│   ├── PHS.rodents.ASV_Meta_Decont_final.RData # Decontaminated 16S ASV and metadata object
│   └── weighted_nsti.tsv.gz         # Weighted NSTI values per sample (PICRUSt2 quality metric)
└── github.Rproj                     # RStudio project file

```
