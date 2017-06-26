---
layout: page
title: "Michael I Love"
---

<!-- {% include JB/setup %} -->

<img style="float: right;" src="http://mikelove.nfshost.com/img/michaellove_sm.jpg"> <br>

michaelisaiahlove at gmail dot com *

\* for software questions, do not email, <br>
instead use the [Bioconductor support site](https://support.bioconductor.org)

<br><br>

Assistant Professor <br>
[Department of Biostatistics](http://sph.unc.edu/bios/biostatistics/) <br>
[Department of Genetics](http://www.med.unc.edu/genetics/) <br>
University of North Carolina-Chapel Hill

[@mikelove](http://twitter.com/mikelove) <br>
[Google Scholar](https://scholar.google.com/citations?user=vzXv764AAAAJ)
[Biostatistics Dept. bio](http://sph.unc.edu/adv_profile/michael-love-phd/)

---

### Research

I use statistical models to infer biologically meaningful
patterns from high-throughput sequencing data, and develop
open-source statistical software for the Bioconductor Project.
One of my main research efforts is in authoring and maintaining the
[DESeq2 package](http://bioconductor.org/packages/DESeq2) for statistical
analysis of RNA-seq experiments.

### Background

From 2013-2016, I was a Postdoctoral Fellow in the group of
Rafael Irizarry in the Biostatistics and Computational Biology
Department at the Dana-Farber Cancer Institute and the Harvard
TH Chan School of Public Health.
I completed a PhD in Computational Biology and Scientific Computing
(2013) in the Vingron Department at the Max Planck Institute for
Molecular Genetics in Berlin and the Mathematics and Informatics
Department of the Freie Universität, Berlin.  I completed a Statistics
M.S. (2010) and Mathematics B.S. (2005) at Stanford University.

### Latest work

My latest work is studying the effect of fragment sequence bias
(e.g. fragment-level GC content bias) on
RNA-seq transcript abundance estimation. I have developed a novel
[method](http://www.nature.com/nbt/journal/v34/n12/full/nbt.3682.html) and
[software](http://bioconductor/packages/alpine) for correcting fragment
sequence bias for the purposes of transcript quantification in
RNA-seq, which greatly reduces the technical artifacts and batch
effects when compared to state-of-the-art methods.

In addition, I collaborate with the authors and developers of
the [Salmon](https://combine-lab.github.io/salmon/) 
software, to incorporate fragment sequence bias correction
into the fast, lightweight transcript abundance estimation methods.
The [Salmon method](http://www.nature.com/nmeth/journal/vaop/ncurrent/full/nmeth.4197.html)
is now published in Nature Methods (March 2017).

There is a connection between the work in bias correction, transcript
abundance estimation, and gene-level differential expression. Because
the biases estimated by Salmon are incorporated as effective
transcript lengths (following the method introduced by 
[Roberts 2011](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2011-12-3-r22)),
and because effective transcript lengths are incorporated and passed
along to the statistical models when using the 
[tximport](http://bioconductor.org/packages/tximport) pipeline,
any biases estimated and corrected for by Salmon (or Sailfish or
kallisto) will be propogated to the differential expression tools,
such as DESeq2. DESeq2 analyzes the estimated counts, but takes into
account factors affecting those counts, such as differences in sequencing
depth, as well as technical or biological changes in genes' effective
lengths. 
