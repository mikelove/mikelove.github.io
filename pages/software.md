---
layout: page
title: "Software"
---

### Maintained by Love Lab

**highly used**

[DESeq2](http://bioconductor.org/packages/DESeq2) (Bioc)
Estimate variance-mean dependence in count data from high-throughput
sequencing assays and test for differential expression based on a
model using the negative binomial distribution.
Collaboration with Simon Anders and Wolfgang Huber (EMBL Heidelberg).

[tximport](http://bioconductor.org/packages/tximport) (Bioc)
Imports transcript-level abundance, estimated counts and transcript
lengths, and summarizes into matrices for use with downstream
gene-level analysis packages such as edgeR, DESeq2, limma-voom.
Collaboration with Charlotte Soneson and Mark Robinson (UZH Zürich)

---

**newly developed**

[apeglm](http://bioconductor.org/packages/apeglm) (Bioc) Bayesian
shrinkage estimators for effect sizes for a variety of GLM models,
using approximation of the posterior for individual coefficients.
Developed by Anqi Zhu (UNC-CH), collaboration with Joseph Ibrahim
(UNC-CH). `apeglm` methods be accessed via `lfcShrink` in
the [DESeq2](http://bioconductor.org/packages/DESeq2) package.

[tximeta](https://github.com/mikelove/tximeta) (GitHub) Import
transcript abundances with automagic population of metadata.
Builds on top of `tximport`, outputs a `SummarizedExperiment` object
with transcriptome metadata automatically added. Collaboration with
Rob Patro (SBU), Charlotte Soneson (UZH), and Peter Hickey (JHU).

---

[alpine](http://bioconductor/packages/alpine) (Bioc)
Modeling and correcting fragment sequence bias for RNA-seq transcript
abundance estimation. 
Collaboration with Rafael Irizarry (DFCI Boston).

[exomeCopy](http://bioconductor.org/packages/exomeCopy) (Bioc)
Detection of copy number variants (CNV) from exome sequencing samples,
including unpaired samples. The package implements a hidden Markov
model which uses positional covariates, such as background read depth
and GC-content, to simultaneously normalize and segment the samples
into regions of constant copy count.
Collaboration with Alena van Bömmel, Stefan Haas and Martin Vingron
(MPI Berlin).

[SparseData](http://github.com/mikelove/SparseData) (GitHub)
Efficiently calculate statistics such as group mean, standard
deviation and t-statistics on large sparse genomic data sets.

### Contributor

[Salmon](https://combine-lab.github.io/salmon/) a tool for quantifying
the expression of transcripts using RNA-seq data. I collaborate with
the lead author and maintainer Rob Patro (SBU) on bias correction methods in
Salmon, similar to those in alpine, on measurements of estimation
uncertainty through Gibbs and bootstrap sampling, and on propagation
of metadata from abundance estimation to downstream analysis packages.

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
This package provides a SummarizedExperiment object of read counts in
genes for an RNA-Seq experiment on four human airway smooth muscle
cell lines treated with dexamethasone.
The citation for the experiment is:
[Himes BE et al (2014)](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4057123/).

[fission](http://bioconductor.org/packages/release/data/experiment/html/fission.html)
This package provides a SummarizedExperiment object of read counts in
genes for a time course RNA-Seq experiment of fission yeast
(Schizosaccharomyces pombe) in response to oxidative stress (1M
sorbitol treatment) at 0, 15, 30, 60, 120 and 180 mins.
The citation for the experiment is:
[Leong HS et al. (2014)](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4050258/).

[parathyroidSE](http://bioconductor.org/packages/release/data/experiment/html/parathyroidSE.html)
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

[alpineData](https://bioconductor.org/packages/alpineData)
This packages provides a subset of alignments for demonstration of
`alpine`. The samples aligned are a subset of 4 samples from the
GEUVADIS project. The citation for the GEUVADIS project is:
[Lappalainen et al (2013)](http://www.nature.com/nature/journal/v501/n7468/full/nature12531.html?WT.ec_id=NATURE-20130926)
