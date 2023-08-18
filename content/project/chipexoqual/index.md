---
title: "ChIPexoQual"
excerpt: "A quality control pipeline for ChIP-exo/nexus data"
date: 2017-09-06
author: "Rene Welch"
draft: false
tags:
  - genomics
categories:
  - R
  - genomics
  - QC
  - ChIP-exo
  - ChIP-nexus
# layout options: single or single-sidebar
layout: single
---

## [ChIPexoQual](https://bioconductor.org/packages/release/bioc/html/ChIPexoQual.html) is a quality control pipeline for ChIP-exo/nexus data.

ChIP-exo/nexus experiments rely on innovative modifications of the commonly used ChIP-seq protocol for high resolution mapping of transcription factor binding sites. Although many aspects of the ChIP-exo data analysis are similar to those of ChIP-seq, these high throughput experiments pose a number of unique quality control and analysis challenges. We develop a novel statistical quality control pipeline and accompanying R/Bioconductor package, ChIPexoQual, to enable exploration and analysis of ChIP-exo and related experiments. ChIPexoQual evaluates a number of key issues including strand imbalance, library complexity, and signal enrichment of data. Assessment of these features are facilitated through diagnostic plots and summary statistics computed over regions of the genome with varying levels of coverage.

This work was published on [Nucleic Acids Research](https://academic.oup.com/nar/article/45/15/e145/4056229)
