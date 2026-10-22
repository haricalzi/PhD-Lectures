# Counterfactual Explanations on Patient Similarity Networks

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/haricalzi/PhD-Lectures/blob/main/Bioinformatics/XAI_PSN.ipynb)

Hands-on lab for the guest lecture *Counterfactual Explanations of Biomedical Graphs for the Interpretability of Clinical Predictions*, Bioinformatics course 2026-2027, Università degli Studi di Milano.

## Contents

The notebook [`XAI_PSN.ipynb`](XAI_PSN.ipynb) goes through:

1. loading the ROSMAP multi-omics dataset (mRNA, DNA methylation, miRNA; Alzheimer's disease vs. controls)
2. preprocessing
3. building one Patient Similarity Network per omic and fusing them with SNF
4. training a GraphSAGE model to classify patients
5. explaining a prediction with gradient saliency
6. generating a counterfactual explanation with CE-GNN

## How to run

Click the **Open in Colab** badge above and run the cells in order. A CPU runtime is enough, and the dataset is downloaded automatically.

To run it locally instead, open the notebook in Jupyter: the first cell installs the required packages.

## Author

Hari Calzi · [hari.calzi@unimi.it](mailto:hari.calzi@unimi.it)
