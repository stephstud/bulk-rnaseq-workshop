---
layout: default
title: Introduction to Bulk RNA-seq Analysis
description: A practical RNA-seq analysis workshop at Monash University Malaysia
---

<p style="text-align: center;">
<img src="4-additional-content/Monash-University-Monash-BDI-locked-element-for-digital-sponsorship-SMC-18012016.jpg" alt="Monash Biomedicine Discovery Institute" width="240">
</p>

<div class="workshop-banner">
  <h1>Introduction to Bulk RNA-seq Analysis</h1>
  <div class="banner-details">
    <div>November 2-3, 2026</div>
    <div><strong>Instructor:</strong> Stephanie Studniberg</div>
  </div>
</div>

This 1.5-day workshop introduces the principles and practical analysis of bulk RNA sequencing (RNA-seq) data. Participants will learn about the complete RNA-seq workflow,
from raw sequencing reads to biological interpretation, and gain hands-on experience analysing gene-count data in R.

The workshop combines short theory sessions with practical exercises covering quality control, data visualisation, differential expression analysis and pathway enrichment.
The final session gives participants time to apply the workflow to their own data with instructor support.

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


## General information

- **Audience:** Researchers, postgraduate students and biologists interested in RNA-seq analysis
- **Prerequisites:** Basic familiarity with R is helpful but not essential
- **Duration:** 1.5 days
- **Location:** Monash University Malaysia

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

The practical sessions will use a gene-count matrix and sample metadata. The introductory lecture will cover the broader workflow, including processing raw FASTQ files.

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