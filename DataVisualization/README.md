# AI-Driven Cardiac Prevention: a Data Visualization Lab

| Version | Notebook | |
|---|---|---|
| 🇬🇧 English | [`AI-Driven_Cardiac_Prevention_EN.ipynb`](AI-Driven_Cardiac_Prevention_EN.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/haricalzi/PhD-Lectures/blob/main/DataVisualization/AI-Driven_Cardiac_Prevention_EN.ipynb) |
| 🇮🇹 Italiano | [`AI-Driven_Cardiac_Prevention_IT.ipynb`](AI-Driven_Cardiac_Prevention_IT.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/haricalzi/PhD-Lectures/blob/main/DataVisualization/AI-Driven_Cardiac_Prevention_IT.ipynb) |

Hands-on lab on data visualization and machine learning applied to clinical data, Università degli Studi di Milano. The two notebooks have the same content and code.

## Contents

The notebook goes through:

1. loading the [Heart Failure Clinical Records](https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records) dataset from the UCI repository (299 patients, 12 clinical features, death event as outcome)
2. exploratory data visualization: histograms, count plots, boxplots and scatter plots
3. clustering the patients with K-Means, choosing $k$ with the elbow and silhouette methods
4. visualizing the clusters in 2D with PCA, before and after feature standardization
5. profiling the clusters with heatmaps, boxplots, count plots and statistical tests
6. checking whether the clusters reflect the clinical risk of death
7. training a decision tree and a Random Forest to predict death, and comparing feature importances with the ones that drive the clustering

## How to run

Click one of the **Open in Colab** badges above and run the cells in order. A CPU runtime is enough, and the dataset is downloaded automatically.

To run it locally instead, open the notebook in Jupyter: the first cell installs the required packages.

## Author

Hari Calzi · [hari.calzi@unimi.it](mailto:hari.calzi@unimi.it)
