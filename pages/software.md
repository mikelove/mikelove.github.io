---
layout: page
title: 
---

### Maintainer

[DESeq2](http://bioconductor.org/packages/DESeq2) (Bioc)
Estimate variance-mean dependence in count data from high-throughput
sequencing assays and test for differential expression based on a
model using the negative binomial distribution.
Collaboration with Simon Anders and Wolfgang Huber (EMBL Heidelberg).

[alpine](http://github.com/mikelove/alpine) (github)
Modeling and correcting fragment sequence bias for RNA-seq transcript
abundance estimation. 
Collaboration with Rafael Irizarry (DFCI Boston).

[tximport](https://bioconductor.org/packages/tximport) (Bioc)
Imports transcript-level abundance, estimated counts and transcript
lengths, and summarizes into matrices for use with downstream
gene-level analysis packages such as edgeR, DESeq2, limma-voom.
Collaboration with Charlotte Soneson and Mark Robinson (UZH Zürich)

[exomeCopy](http://bioconductor.org/packages/exomeCopy) (Bioc)
Detection of copy number variants (CNV) from exome sequencing samples,
including unpaired samples. The package implements a hidden Markov
model which uses positional covariates, such as background read depth
and GC-content, to simultaneously normalize and segment the samples
into regions of constant copy count.
Collaboration with Alena van Bömmel, Stefan Haas and Martin Vingron
(MPI Berlin).

[SparseData](http://github.com/mikelove/SparseData) (github)
Efficiently calculate statistics such as group mean, standard
deviation and t-statistics on large sparse genomic data sets.

### Contributor

[GenomicFiles](http://bioconductor.org/packages/GenomicFiles) (Bioc)
This package provides infrastructure for parallel computations
distributed 'by file' or 'by range'. User defined MAPPER and REDUCER
functions provide added flexibility for data combination and manipulation.
Collaboration with Valerie Obenchain and Martin Morgan (Bioconductor
core team).

[rafalib](https://cran.r-project.org/web/packages/rafalib/index.html) (CRAN)
A series of shortcuts for routine tasks.
Collaboration with Rafael Irizarry (DFCI Boston).

### Data packages

[airway](http://bioconductor.org/packages/release/data/experiment/html/airway.html)
(Bioc)
This package provides a SummarizedExperiment object of read counts in
genes for an RNA-Seq experiment on four human airway smooth muscle
cell lines treated with dexamethasone.
The citation for the experiment is:
[Himes BE et al (2014)](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4057123/).

[fission](http://bioconductor.org/packages/release/data/experiment/html/fission.html)
(Bioc) 
This package provides a SummarizedExperiment object of read counts in
genes for a time course RNA-Seq experiment of fission yeast
(Schizosaccharomyces pombe) in response to oxidative stress (1M
sorbitol treatment) at 0, 15, 30, 60, 120 and 180 mins.
The citation for the experiment is:
[Leong HS et al. (2014)](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4050258/).

[parathyroidSE](http://bioconductor.org/packages/release/data/experiment/html/parathyroidSE.html)
(Bioc) 
This package provides SummarizedExperiment objects of read counts in
genes and exonic parts for paired-end RNA-Seq data from experiments on
primary cultures of parathyroid tumors.
The citation for the experiment is:
[Haglund F et al (2012)](http://www.ncbi.nlm.nih.gov/pubmed/23024189).

[tximportData](https://bioconductor.org/packages/tximportData)
This packages provides output files from common transcript estimation
software (Salmon, Kallisto, RSEM, Cufflinks) for demonstration of
import using `tximport`. The files are a subset of 6 samples from the
GEUVADIS project. The citation for the GEUVADIS project is:
[Lappalainen et al (2013)](http://www.nature.com/nature/journal/v501/n7468/full/nature12531.html?WT.ec_id=NATURE-20130926)
