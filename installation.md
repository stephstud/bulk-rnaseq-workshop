---
layout: default
title: Installation instructions
description: Software setup for the Introduction to Bulk RNA-seq Analysis workshop
---

# Installation instructions

Please complete this setup **before** the workshop starts. If you run into any problems, email stephanie.studniberg@monash.edu.

## 1. Install R and RStudio

- Install R, version 4.6.0 or later (this workshop was built and tested on R 4.6.0), from [CRAN](https://cran.r-project.org/)
- Install [RStudio Desktop](https://posit.co/download/rstudio-desktop/)

If you already have R installed, check your version first by running `R.version.string` in the console, and update if it's older than 4.6.0.

## 2. Install BiocManager

Several of the packages used in this workshop come from Bioconductor rather than CRAN, so you'll need `BiocManager` to install them. Open RStudio and run:

```r
install.packages("BiocManager")
```

## 3. Install the required packages

Copy and run the following in the R console:

```r
install.packages(c("ggplot2", "tidyr", "pheatmap", "patchwork", "ggrepel", "RColorBrewer", "circlize", "matrixStats", "scales", "tmod", "renv", "workflowr"))

BiocManager::install(c("edgeR", "limma", "rtracklayer", "Rsubread", "ComplexHeatmap", "Glimma", "clusterProfiler", "enrichplot", "org.Hs.eg.db"))
```

## 4. Check your setup

Run the following and confirm every line completes without error:

```r
library(edgeR)
library(limma)
library(rtracklayer)
library(Rsubread)
library(ComplexHeatmap)
library(Glimma)
library(clusterProfiler)
library(enrichplot)
library(org.Hs.eg.db)
library(ggplot2)
library(tidyr)
library(pheatmap)
library(patchwork)
library(ggrepel)
library(RColorBrewer)
library(circlize)
library(matrixStats)
library(scales)
library(tmod)
library(renv)
library(workflowr)
```

If any `library()` call fails, re-run the install command for that package and try again before the workshop.
