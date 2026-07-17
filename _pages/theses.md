---
layout: single
title: "Available Theses"
permalink: /theses/
author_profile: true
---

{% include base_path %}

<style>
.thesis{
  border:1px solid var(--global-border-color);
  border-left:4px solid var(--global-link-color);
  border-radius:8px;
  padding:1.1em 1.5em 1.25em;
  margin:1.25em 0;
  background:var(--global-bg-color);
}
.thesis h3{margin-top:.3em;text-align:left;}
.thesis p{text-align:left;hyphens:none;}
.thesis .meta{font-size:.92em;margin:.5em 0 0;}
.thesis .meta strong{color:var(--global-link-color);}
</style>

I am always looking for motivated **Bachelor's and Master's students** interested in AI for biology
and medicine. The projects below build on **DECODE-RNA**, our single-cell RNA transformer-based
model. If any of them sound interesting — or if you have your own idea in a related area — feel free
to [get in touch](mailto:andrea.tangherloni@unibocconi.it) to discuss it.

<div class="thesis" markdown="1">
### Systematic Ablations, New Pre-training Objectives, and Scaling Behaviour for a Single-Cell Foundation Model

Investigate which design choices actually drive the quality of DECODE-RNA's learned cell representations — the expression-encoding scheme, protein-language-model priors, the dual-attention structure, and the multi-task curriculum — through controlled ablations measured on both in-distribution accuracy and cross-tissue transfer. Introduce new self-supervised objectives that teach the model to distinguish genuine biological silence from technical dropout, and characterise how representation quality scales with data and model size. First validated on blood and PBMC cells, then extended to whole-body Census data and multi-GPU training to derive a scale-aware pre-training recipe.

<p class="meta"><strong>Required:</strong> solid Python and PyTorch; understanding of deep learning fundamentals (transformers, attention, self-supervised/masked pre-training, optimisation, and learning-rate schedules); ability to design controlled experiments and rigorously interpret training curves.</p>

<p class="meta"><strong>A plus:</strong> PyTorch Lightning; experience running jobs on a GPU/Slurm cluster and with multi-GPU (DDP) training; basic familiarity with single-cell RNA-seq and Scanpy/AnnData (can be learned on the job).</p>
</div>

<div class="thesis" markdown="1">
### Multi-Teacher Knowledge Distillation from Single-Cell Foundation Models

Build a framework that distils the complementary strengths of several existing single-cell foundation models (e.g., scGPT, Geneformer, UCE, scVI) into DECODE-RNA's unified gene vocabulary and continuous-expression representation. Because the teacher models live in incompatible embedding spaces, the central challenge is cross-space alignment: preserving each teacher's cell–cell similarity structure and learning per-teacher weighting so the student inherits batch correction, biological resolution, and gene-level knowledge from the most reliable source. First tested on a foetal reference dataset using standard data-integration metrics, then evaluated on cross-tissue transfer against each individual teacher.

<p class="meta"><strong>Required:</strong> strong Python and PyTorch; grasp of representation learning and the core idea of knowledge distillation; comfort working with embeddings and similarity/contrastive objectives.</p>

<p class="meta"><strong>A plus:</strong> familiarity with pretrained model ecosystems (running inference with scGPT, Geneformer, UCE, scVI, and managing their environments); notions of representation alignment (e.g., CKA, Procrustes); single-cell data integration metrics (scib) and Scanpy/AnnData.</p>
</div>

<div class="thesis" markdown="1">
### Validating Attention-Derived Gene Regulatory Networks Against Experimental Ground Truth

Test whether the gene–gene relationships DECODE-RNA extracts from its cross-attention weights reflect real biological regulation rather than mere co-expression. Build an evaluation harness that benchmarks the model's zero-shot networks against curated regulons and experimental evidence (DoRothEA/CollecTRI, ChIP-seq, and perturbation data), and compares them with established network inference methods such as GENIE3, SCENIC, and CellOracle. First applied to blood cell types, then extended to further tissues to assess how cell-type-specific and transferable the inferred regulation is. This project is more biology-leaning and less deep-learning-heavy.

<p class="meta"><strong>Required:</strong> Python and data analysis; a computational-biology/bioinformatics background with an understanding of gene regulation (transcription factors and their targets); sound evaluation methodology (AUROC/AUPRC, precision–recall, benchmarking design).</p>

<p class="meta"><strong>A plus:</strong> familiarity with regulatory resources (DoRothEA/CollecTRI, ChIP-seq/ChIP-Atlas, perturbation datasets) and network-inference tools (GENIE3, SCENIC, CellOracle); Scanpy/AnnData for single-cell handling.</p>
</div>
