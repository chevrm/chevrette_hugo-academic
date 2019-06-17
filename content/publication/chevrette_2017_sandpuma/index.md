---
abstract: Nonribosomally synthesized peptides (NRPs) are natural products with widespread applications in medicine and biotechnology. Many algorithms have been developed to predict the substrate specificities of nonribosomal peptide synthetase adenylation (A) domains from DNA sequences, which enables prioritization and dereplication, and integration with other data types in discovery efforts. However, insufficient training data and a lack of clarity regarding prediction quality have impeded optimal use. Here, we introduce prediCAT, a new phylogenetics-inspired algorithm, which quantitatively estimates the degree of predictability of each A-domain. We then systematically benchmarked all algorithms on a newly gathered, independent test set of 434 A-domain sequences, showing that active-site-motif-based algorithms outperform whole-domain-based methods. Subsequently, we developed SANDPUMA, a powerful ensemble algorithm, based on newly trained versions of all high-performing algorithms, which significantly outperforms individual methods. Finally, we deployed SANDPUMA in a systematic investigation of 7635 Actinobacteria genomes, suggesting that NRP chemical diversity is much higher than previously estimated. SANDPUMA has been integrated into the widely used antiSMASH biosynthetic gene cluster analysis pipeline and is also available as an open-source, standalone tool.
authors:
- admin
- Fabian Aicheler
- Oliver Kohlbacher
- Cameron R Currie
- Marnix H Medema
date: "2017-10-15T00:00:00Z"
doi: "10.1093/bioinformatics/btx400"
featured: true
image:
  caption: ""
  focal_point: ""
  preview_only: false
projects: []
publication: '*Bioinformatics, 33*(20)'
publication_short: ""
publication_types:
- "2"
publishDate: "2017-10-15T00:00:00Z"
slides: ""
summary: New machine-learning method for substrate specificity prediction of nonribosomal peptide adenylation domains.
tags:
- software
title: SANDPUMA - ensemble predictions of nonribosomal peptide chemistry reveal biosynthetic diversity across Actinobacteria
url_code: ""
url_dataset: ""
url_pdf: "files/Chevrette_Bioinfo_2017.pdf"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---