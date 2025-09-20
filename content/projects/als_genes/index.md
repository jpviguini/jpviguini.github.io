---
title: "Gene Discovery in ALS with Language Models"
date: 2025-01-01
grad: "grad-1"
draft: false
project_tags: ["Embedding models", "AI", "Bioinformatics", "NLP", "Python"]
summary: "Prioritizing causal genes in ALS by integrating statistical genetics with word embeddings from biomedical literature."
categories: ["research"]
params:
  index: 1
weight: 1

---

<div style="text-align: center; margin-bottom: 3rem;">
  <img src="/images/genes/featured.jpg" alt="Gene similarity network for ALS"></img>
</div>


## 🧬 Gene Prioritization in ALS with Language Models  
**Prioritizing causal genes in ALS by integrating statistical genetics with word embeddings from biomedical literature.**  

📅 **Research Period:** Jul 2025 – Jul 2026 [currently in development]

🌐 **GitHub:** [Gene discovery](https://github.com/jpviguini/als-genes)  


**This research is supported by a FAPESP undergraduate fellowship** ([grant link](https://bv.fapesp.br/en/bolsas/228539/temporal-prediction-of-genetic-associations-in-als-through-nlp-and-complex-network-analysis/)).  



### Overview

**Amyotrophic Lateral Sclerosis (ALS)** is a progressive and fatal neurodegenerative disorder with complex genetic roots. A major challenge in understanding ALS is translating findings from Genome-Wide Association Studies (GWAS) into biological insights. GWAS can identify genomic regions associated with the disease, but these regions often contain multiple genes, making it incredibly difficult to pinpoint the single **true causal gene** responsible for the association.


This project addresses this critical bottleneck by developing a novel computational framework that integrates **statistical genetics** with **Natural Language Processing (NLP)**. We use advanced language models, like BioBERT and fastText, to analyze a vast corpus of biomedical literature. By learning how genes are described and functionally related in scientific papers, we can create "biologically informed" models with **word embeddings** that guide the statistical analysis, dramatically improving our ability to identify high-confidence candidate genes for ALS.



### How does it work?

The methodology is a multi-stage pipeline designed to bridge the gap between statistical association and biological function.

**1. Data Acquisition & Corpus Building**

First, we gather two primary types of data: large-scale ALS GWAS summary statistics (containing data from over 27,000 cases and 122,000 controls) and a specialized text corpus built from approximately 70,000 PubMed article abstracts related to ALS genetics.

**2. Learning Gene Function with Word Embeddings**

Using the text corpus, we train language models (BioBERT) to generate "gene embeddings": numerical vector representations for every gene. These embeddings capture the aggregated functional profile of a gene based on its context across thousands of research articles. This allows us to quantify the functional relationships between genes.

**3. Integrating Biological Priors into Fine-Mapping**

This is the core innovation. Instead of assuming all genes in a GWAS locus are equally likely to be causal, we use our embeddings to calculate a "prior probability" for each gene. Genes that are semantically similar to well-established ALS genes (like <i>SOD1</i> or <i>C9orf72</i>) receive a higher initial probability. This prior knowledge is then integrated into a Bayesian fine-mapping model (FINEMAP) to refine the GWAS signals.

**4. Gene Prioritization and Validation**

The final output is a ranked list of candidate genes supported by both statistical evidence from patient data and functional evidence from the literature. We performed a temporal validation by training a model on literature before 2010 and successfully "predicted" the discovery of the ALS gene *KIF5A* (which was only linked to ALS in 2018), demonstrating the powerful predictive capability of the framework.

Here is a diagram illustrating how we calculate the functional similarity between a candidate gene and known ALS genes:

<div style="text-align: center; margin-top: 20px;">
  <img src="/images/genes/featured2.jpg" alt="Diagram of cosine similarity calculation for gene embeddings" style="max-width: 80%;"></img>
  <p style="font-size: 0.9em; color: #666; margin-top: 5px;">The relevance score for a candidate gene is the maximum cosine similarity between its vector and the vectors of known ALS genes.</p>
</div>



### Authors  

<div style="font-size: 0.9em;">
<strong>João Pedro Viguini T. T. Correa</strong> – Undergraduate Research Fellow (FAPESP), University of São Paulo (USP)  

<strong>Ricardo Cerri</strong> – Assistant Professor, University of São Paulo (USP)  
</div>





