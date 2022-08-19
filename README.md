# *Dissertation*

This repository documents all the steps taken in order to develop a customer micro-segmentation of the clients of a corporate bank. For the purpose of data privacy, the dataset utilised cannot be uploaded within the repository. Nonetheless, the Notebooks take necessarry precautions to ensure that all of the data and processess are well explained in order not to cause any inconvenience to the reader.

## Summary Report

The summary report contains the most recent and updated Jupyter Notebook file documenting and summarising the entirety of the process. Throughout the Notebook, the reader can follow the steps that were taken in order to interpret, visualise, transform and cluster the data.

Within the file, only the most relevant and important codes were kept to ensure greater readability. However, the other subsections of this repository contain the whole Notebooks that thoroughly document the individual steps of the process. The other notebooks report both the final codes and codes that were not utilised/ were not significant at the end. For that matter the other notebooks are quite lengthy and contain redundant information. As a consequence the reader is advised to read the summary report first and utilise the other notebooks in case of issues or doubts. 

The summary report Notebook is organized as follows:
  - The data is presented and explained
  - The missing values and zero values are assessed
  - The features are visualised
  - The data is transformed to accomodate a clustering process
  - The data is standardised, normalised and divided within two datasets
  - The models are applied to the original dataset and to dimensionally reduced datasets
  - The clusters are visualised and explained.

## Data Mining

This section contains a Jupyter Notebook which assesses the initial dataset provided by Zeb Consultancy. Within the Notebook the data is foremost described and explained and then the most significant issues are presented. 

Once the issues are clearly stated, the features and their respective distributions are graphed for the reader to better understand the data types, characteristics and statistics.

## Data Transformation

This section is devoted to the transformation of the dataset prior to the data modelling. Within this section, two Notebooks are present:

  - *Data Transformation*
  - *Web Scraping*.

The former Notebook wants to transform the features which presented issues in the *Data Mining* Notebook. Precisely, it tackles missing/ zero values and corrects skewed distributions.

The latter Notebook, on the other hand, utilises web-scraping techniques in order to collect more data. Specifically, it collects data from German postcodes to geographically segment the observations of the dataset. It is important to note that the codes in the web scraping notebook were not utilised at the end of the process.

## Data Correction

This section is devoted to the last corrections prior to the modelling of the dataset. Specifically, the branch contains a Notebook which normalises and standardises the dataset. The Notebook also separates the dataset into two new datasets. By doing so, the research can achieve greater accuracy and validity in later clustering.

## Data Modelling

The data modelling applies clustering techniques to the original datasets. These datasets were merely featured engineered. The models applied to said datasets are the following:

  - *K-Means*
  - *Hierarchical Clustering*
  - *K-Modes*
  - *FasterPAM*
  - *DBSCAN*
  - *HDBSCAN*
  - *Fuzzy C-Means*
 
Within this notebook all the models were tested for all distance metrics (Python packages permitting). Within the next notebooks only the best distance metrics for each model are utilised. For the sake of readability, each modelling technique is reported and summarised within a new Notebook. 

## PCA Data Modelling

Within this section, the datasets are foremost dimensionally reduced through the application of Principal Component Analysis. Following the reduction of the datasets, data modelling techniques are applied to the datasets. The models applied are the following:

  - *K-Means*
  - *Hierarchical Clustering*
  - *FasterPAM*
  - *DBSCAN*
  - *Fuzzy C-Means*

Within this and future notebooks, *HDBSCAN* and *K-Medoids* were not adopted. This was due to the greater performance of analogous algorithms (i.e. *DBSCAN* and *FasterPAM* respectively) within the Original Dataset. For the sake of readability, each modelling technique is reported and summarised within a new Notebook.

## ICA Data Modelling

Within this section, the datasets are dimensionally reduced via Independent Component Analysis. Following the reduction of the datasets, data modelling techniques are applied to the datasets. The models applied are the following:

  - *K-Means*
  - *Hierarchical Clustering*
  - *FasterPAM*
  - *Fuzzy C-Means*

Given the high computational complexity of *DBSCAN* and its poor performance within the Original and PCA datasets compared to other algorithms, the model was disregarded within this and future notebooks. For the sake of readability, each modelling technique is reported and summarised within a new Notebook.

## t-SNE Data Modelling

Within this section, the datasets are dimensionally reduced via t-SNE. Following the reduction of the datasets, data modelling techniques are applied to the datasets. The models applied are the following:

  - *K-Means*
  - *Hierarchical Clustering*
  - *FasterPAM*
  - *Fuzzy C-Means*

For the sake of readability, each modelling technique is reported and summarised within a new Notebook.

## UMAP Data Modelling

Within this section, the datasets are dimensionally reduced via Uniform Manifold Approximation and Projection. Following the reduction of the datasets, data modelling techniques are applied to the datasets. The models applied are the following:

  - *K-Means*
  - *Hierarchical Clustering*
  - *FasterPAM*
  - *Fuzzy C-Means*

For the sake of readability, each modelling technique is reported and summarised within a new Notebook.

## Cluster Explanation

This section selects the best models according to pre-defined performance metrics and reports the main findings, both visually and in written form.

## Granular Segmentation

This section was devoted to an excercise later deemed inefficient and redundant. Specifically, the research wanted to segment the datasets even further to then apply the clustering techniques. While this would have provided more granular results, the modelling was not aligned with the initial objective of the research and the clustering results did not prove as efficient as initially hoped for. Consequentially, the idea was dropped but the Notebook was kept as a reference.
