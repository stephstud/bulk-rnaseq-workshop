---
layout: default
title: Introduction to Bulk RNA-seq Analysis
description: A practical RNA-seq analysis workshop at Monash University Malaysia
---

<div class="workshop-header">
  <h1>Introduction to Bulk RNA-seq Analysis</h1>
  <img src="4-additional-content/Monash-University-Monash-BDI-locked-element-for-digital-sponsorship-SMC-18012016.jpg" alt="Monash Biomedicine Discovery Institute" width="200">
</div>
<div class="banner-details">
  <div>December 2-3, 2026</div>
</div>


## General Information
In this 1.5 day workshop, you will learn how to analyse RNA-seq data from raw counts through to pathway enrichment using R with an emphasis on the limma-voom analysis workflow.
This will include learning how to read in count data, perform quality control, identify and adjust for confounding variation and batch effects, perform differential expression analysis, 
pathway enrichment and gene set testing. You will also generate plots associated with the workflow, including PCA/MDS plots, volcano plots, and heatmaps. The final session 
will give participants time to apply the workflow to their own data with instructor support.

**Who this workshop is for:** This workshop is aimed at biologists (graduate students and other researchers) intending to perform differential expression analysis of bulk RNA-seq data in R. Please note that basic
R knowledge is assumed, and this is not an introduction to R course.

**Requirements:** Participants must bring a laptop with the specific software packages installed. 

**Contact:** Please email stephanie.studniberg@monash.edu for more information.

---

## Content

This course is an introduction for how to approach bulk RNA-seq data, starting from a raw counts object. It will provide an overview of the fundamentals of RNA-seq analysis, including:

* Quality control of raw counts, filtering and normalisation
* Data exploration with PCAs and MDS plots
* Identifying adjusting for confounding variables and batch effects
* Differential expression analysis and data visualisation
* Pathway enrichment analysis


## Learning outcomes

A student who has met the objectives of the course will be able to:

* Gain insight into how to design an RNA-seq experiment
* Analyse bulk RNA-seq data using the R packages edgeR and limma
* Know best practices for performing differential expression analysis
* Annotate and interpret their results

---

## Schedule (November 2-3 2026)

### Day 1 morning

**Lecture**

- Intro to RNA-seq
- Experimental design considerations
- Overview of DE analysis
- QC, filtering, normalisation

**Practical**

- Load counts and metadata
- Calculate and visualise sequencing stats
- Add annotation
- QC, filtering, normalisation

### Day 1 afternoon

**Lecture**

- Data visualisation
- Identifying and adjusting for variation
- Checking variation is removed successfully
- DE analysis

**Practical**

- Identifying and adjusting for variation (MDS plots)
- Checking variation is removed successfully (BCV plot)
- DE analysis
- Data vis (volcano plots, heatmaps)

### Day 2 morning

**Lecture**

- Pathway enrichment in limma
- Do more with your bulk RNA-seq data

**Practical**

- Pathway enrichment in limma
- Do more with your bulk RNA-seq data (overview of resources available)
- Optional: bring your own data

*The schedule is provisional and may change.*

---

## Lecture materials

Lecture materials will be made available here.

## Practical materials

Practical scripts, example datasets and supporting materials will be made available here.

---

## Software setup

Participants should bring a laptop and complete the software setup before the workshop.

1. Install [R](https://cran.r-project.org/)
2. Install [RStudio Desktop](https://posit.co/download/rstudio-desktop/)
3. Download the workshop materials
4. Complete the pre-workshop setup check

Detailed installation instructions and required R packages will be provided before the workshop.


## Preparing your own data

Participants who wish to work with their own data on Day 2 should bring:

- A gene-count matrix
- A sample metadata table
- A research question and the comparison they wish to investigate

Participants without suitable data can continue using the workshop dataset.