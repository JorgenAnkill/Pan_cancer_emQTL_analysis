# Integrative pan-cancer analysis reveals a common architecture of dysregulated transcriptional networks characterized by loss of enhancer methylation

*Jørgen Ankill, Zhi Zhao, Xavier Tekpli, Elin H. Kure, Vessela N. Kristensen, Anthony Mathelier, Thomas Fleischer*

Contact: Jørgen Ankill, jorgen.ankill2@rr-research.no

#
**Description:**

This repository contains scripts related to the paper "An integrative pan-cancer analysis of DNA methylation and gene expression identifies a common link between aberrant enhancer methylation and proliferation in cancer". 

The code and associated data represent a minimal working example for pan-cancer expression-methylation Quantitative Trait Loci (emQTL) analysis as presented in the manuscript referred to above.

This code performs a correlation analysis between two matrices, metMat and exprMat, which contain normalized expression- and CpG methylation data respectively. DNA methylation levels at all CpGs are correlated with the expression of all genes by Pearson correlation to identify significant CpG-gene associations, i.e., emQTLs. The resulting significant correlations after Bonferroni correction are then grouped by bipartite network analysis using COmplex Network Description Of Regulators (CONDOR) into emQTL communities. 

This example includes 100 random samples, 1000 CpGs, and 1000 genes sourced from The Cancer Genome Atlas pan-cancer (TCGA-PANCAN) data, downloaded from the Xena browser. For more details on the data source, refer to: Goldman M et al. [1]. Data Source: https://xenabrowser.net/datapages/?cohort=GDC%20Pan-Cancer%20(PANCAN)&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443.

**References:**
  1. Goldman, M., et al., The UCSC Xena platform for public and private cancer genomics data visualization and interpretation. bioRxiv, 2019: p. 326470.
