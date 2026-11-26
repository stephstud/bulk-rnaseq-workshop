---
layout: default
title: Installation instructions
description: Software setup for the Introduction to Bulk RNA-seq Analysis workshop
---

# Installation instructions

Please complete this setup **before** the workshop starts. If you run into any problems, email stephanie.studniberg@monash.edu.

## 1. Install R and RStudio

- Install R from [CRAN](https://cran.r-project.org/)
- Install [RStudio Desktop](https://posit.co/download/rstudio-desktop/)

## 2. Install BiocManager

Several of the packages used in this workshop come from Bioconductor rather than CRAN, so you'll need `BiocManager` to install them. Open RStudio and run:

```r
install.packages("BiocManager")
```

## 3. Install the required packages

Copy and run the following in the R console:

```r
install.packages(c("ggplot2", "tidyr", "pheatmap", "RColorBrewer", "cowplot"))

BiocManager::install(c("edgeR", "limma", "rtracklayer", "org.Hs.eg.db", "GO.db", "AnnotationDbi"))
```

## 4. Check your setup

Run the following and confirm every line completes without error:

```r
library(edgeR)
library(limma)
library(rtracklayer)
library(ggplot2)
library(tidyr)
library(pheatmap)
library(RColorBrewer)
library(cowplot)
library(org.Hs.eg.db)
```

If any `library()` call fails, re-run the install command for that package and try again before the workshop.
