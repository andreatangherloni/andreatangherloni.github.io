---
layout: archive
title: "DECODE"
permalink: /decode/
author_profile: true
description: "DECODE — decoding the language of single-cell gene regulation with Transformers. A project funded by the Italian Ministry of University and Research (MUR) through the Fondo Italiano per la Scienza (FIS)."
---

{% include base_path %}

<p class="project-lead" markdown="1">
**DECODE** develops Transformer-based foundation models that learn the language of gene regulation directly from single-cell data, integrating single-cell transcriptomics (scRNA-seq) and chromatin accessibility (scATAC-seq) to infer **Gene Regulatory Networks**: the mechanisms that govern how cells develop and how disease progresses.
</p>

<div class="project-facts" markdown="0">
  <dl>
    <dt>Funder</dt>
    <dd>Ministero dell&rsquo;Universit&agrave; e della Ricerca (MUR)</dd>

    <dt>Programme</dt>
    <dd>Fondo Italiano per la Scienza (FIS)</dd>

    <dt>Scheme</dt>
    <dd>Starting Grant</dd>

    <dt>Year of award</dt>
    <dd>2025</dd>

    <dt>Total funding</dt>
    <dd>&euro; 1.2M</dd>

    <dt>Principal Investigator</dt>
    <dd>Andrea Tangherloni</dd>

    <dt>Host institution</dt>
    <dd>Department of Computing Sciences, Bocconi University, Milan, Italy</dd>
  </dl>
</div>

## Aims
Single-cell sequencing can now profile the transcriptome and the chromatin landscape of millions of individual cells, but turning those measurements into a mechanistic account of *regulation* (i.e., which genes control which, in which cell type, and under which conditions) remains an open problem. DECODE addresses it by treating gene expression as a language and learning its grammar at scale.

The project pursues three objectives:

- Build a **foundation model for single-cell transcriptomics** that learns transferable representations of cells and genes from large, heterogeneous public data.
- **Integrate transcriptomic and chromatin-accessibility data** so that regulatory relationships are inferred from complementary evidence rather than expression correlation alone.
- Derive **Gene Regulatory Networks** that are cell-type-specific, testable against experimental evidence, and useful for studying cell development and disease progression.


## Expected results
- A pre-trained single-cell foundation model with representations that transfer across tissues and datasets, evaluated on both in-distribution accuracy and cross-tissue generalisation.
- A multimodal extension that couples expression with chromatin accessibility for regulatory inference.
- Zero-shot Gene Regulatory Networks benchmarked against curated regulons and experimental evidence, and compared with established network-inference methods.
- Methodological contributions on scaling behaviour, pre-training objectives and evaluation practice for single-cell foundation models.

## Results achieved
This section will be updated as the project progresses, reporting the results obtained and the outputs produced with the support of the funding received.

## Funding
This project is funded by the Italian Ministry of University and Research (MUR) under the **Fondo Italiano per la Scienza (FIS)** — Starting Grant, with Andrea Tangherloni as Principal Investigator at the Department of Computing Sciences, Bocconi University.

<p class="project-note" markdown="1">
Interested in working on these problems? Bachelor's and Master's
[thesis projects]({{ base_path }}/theses/) building on DECODE-RNA are available, and I am always open to collaborations — [get in touch](mailto:{{ site.author.email }}).
</p>