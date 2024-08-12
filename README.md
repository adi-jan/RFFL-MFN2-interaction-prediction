# RFFL-MFN2-interaction-prediction
This repository contains all the necessary information required to reproduce the RFFL-MFN2 interaction prediction using Alphafold2.0 mentioned in the paper.
The pipeline I used in this paper is adopted from [McLean et al., 2024](https://doi.org/10.1099/mic.0.001473).
The pipeline includes three parts:
Part A outputs individual fasta files with _His-SUMO-MFN2_ and _GST-RFFL_ amino acid sequences separated by ":." Here, _GST-RFFL_ is the bait sequence, and _His-SUMO-MFN2_ is the candidate sequence.   
Part B uses [ColabFold_BATCH](https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/batch/AlphaFold2_batch.ipynb) to perform AlphaFold2-based model prediction on the protein pair.
