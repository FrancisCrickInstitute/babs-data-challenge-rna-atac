# Recruitment Data Challenge

The Bioinformatics & Biostatistics Group @ The Francis Crick Institute

### Introduction

Here you will find the data from an RNA-Seq and ATAC-Seq experiment. Both experiments have the same design. There is a treatment and control group each containing three replicates making a total of six samples per experiment. The data files are defined as follows (all files are tab delimited text files):

#### RNA-Seq Data

* rnaseq_design.txt - Sample ids and corresponding condition labels.
* rnaseq_gene_counts.txt - Raw (not normalised) gene-level read counts for each sample.
* rnaseq_annotation.txt - Gene level annotation.

#### ATAC-Seq Data

* atacseq_design.txt - Sample ids and corresponding condition labels.
* atacseq_peak_counts.txt - Raw (not normalised) ATAC-Seq peak level counts for each sample.
* atacseq_peaks.bed - A bed file defining the peak loci

All sequence data were aligned to the human genome reference hg38.

### The Challenge

The treatment here is thought to activate a transcriptional program via remodelling of the chromatin architecture. 

Suggested aims:
1. Identify genes that may be transcriptionally regulated by chromatin remodelling.
2. Identify the possible transcriptional programs involved.
3. Present candidate transcription factors that may be responsible for the underlying regulation.

* **Please produce a 20 minute presentation detailing your exploration of the data, your analysis approach and findings.**
* **Be prepared to discuss the rationale behind your analysis approach, challenges you faced and potential future analysis direction.**
