# RNA-Seq Analysis of TGF-β-Induced EMT Signaling in Cancer Cells

## Overview

This project performs RNA-seq differential expression and pathway analysis to investigate the molecular mechanisms underlying TGF-β–mediated epithelial-to-mesenchymal transition (EMT) and cancer progression.

The analysis is based on transcriptomic data examining the role of the long noncoding RNA **LETS1** in potentiating TGF-β signaling in breast and lung cancer cells.

Using DESeq2 and pathway analysis, the project identifies differentially expressed genes (DEGs), signaling pathways, and molecular interaction networks associated with EMT, migration, and tumor invasiveness.

---
# Dataset Information
- **Title:**  Transcriptome analysis of A549 cells upon lncRNA ectopic LETS1 expression
- **Organism:** Homo sapiens
- **Experiment Type:** Expression profiling by high throughput sequencing
- **Data Source:** GEO Dataset (GSE203159)
- **Data Contributors:**  Fan C, Kuipers T, Mei H, ten Dijke P
- **Publication:** https://www.science.org/doi/10.1126/scisignal.adf1947
  
# Repository Structure

```text
TGFb-EMT-RNAseq-Analysis/
│
├── figures/
│   ├── Dispersion Estimates.png
│   ├── Frequencies of padj values.png
│   ├── GO Biological Process.png
│   ├── Heatmap DEG.png
│   ├── KEGG Pathway Enrichment.png
|   ├── PCA Plot.png
|   ├── PPI Interaction network
│   └── Volcano plot.png
│
├── results/
│   ├── GO_enrichment.tsv
│   ├── KEGG_enrichment.tsv
│   ├── deseq.result.all.tsv
│   └── deseq_deg.tsv
│
├── scripts/
│   └── tgf beta induced EMT RNASeq.R
│
└── README.md
```

