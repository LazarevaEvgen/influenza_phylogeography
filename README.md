# NGS_phylogeography
[`⚡Press here to open the project in Google Collab!`](https://colab.research.google.com/github/LazarevaEvgen/influenza_phylogeography/blob/main/influenza_phylogeography.ipynb)

This is a mini-application designed to optimize the phylogeographic analysis of large-scale Influenza virus datasets.

**What is this tool used for?**

1. **Data Redundancy Elimination:** FASTA alignment sequences are grouped by sampling year and geographic location. Within each group, sequence downsampling is performed using the CD-HIT tool (DOI: 10.1093/bioinformatics/btl158) with a user-specified sequence identity threshold (as an option, the molecular evolution rate of your target genes can be considered when setting this threshold).

* **Interactive Mapping and Spatiotemporal Visualization:** Construct interactive maps to define the circulation zones of your monophyletic groups/lineages of interest. The tool can also be utilized to visualize annual shifts in virus detection areas. Final maps can be exported and downloaded as standalone HTML files.

*Comprehensive instructions, supported header formats, and common troubleshooting examples are detailed within the descriptions of the respective code cells.*

Map Example (Screenshot):
<img width="3032" height="1253" alt="g1355" src="https://github.com/user-attachments/assets/b92c8352-c9ef-4867-afa1-37eb9cfac219" />

Data Downsampling Execution Example (Screenshot):
<img width="3786" height="1650" alt="g2287" src="https://github.com/user-attachments/assets/687f77c4-2cfc-4513-8191-fa56fe92b6b1" />



