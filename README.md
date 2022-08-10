# *Dissertation*

This repository documents all the steps taken in order to develop a customer micro-segmentation of the clients of a corporate bank. For the purpose of data privacy, the dataset utilised cannot be uploaded within the repository. Nonetheless, the Notebooks take necessarry precautions to ensure that all of the data and processess are well explained in order not to cause any inconvenience to the reader.

## *Final Presentation*

The final presentation contains the most recent and updated Jupyter Notebook file documenting and summarising the entirety of the process. Throughout the Notebook, the reader can follow the steps that were taken in order to interpret, visualise, transform and cluster the dataset in order to attain an effienct customer micro-segmentation. 

Within the file, only the most relevant and important codes were kept to ensure greater readability. However, the other subsections of this repository contain the whole Notebooks that thoroughly document the individual steps of the process and contain both the final codes and the codes that were not utilized at the end.

The Notebook is organized as follows:
  - The data is presented and explained
  - The missing values and zero values are assessed
  - The features are visualised
  - The data is transformed to accomodate a clustering process
  - The data is standardised, normalised and divided within two datasets
  - The models are applied to the original dataset and to a dimensionally reduced dataset
  - The clusters are visualised and explained.

## Data Mining

This section contains a Jupyter Notebook which assesses the initial dataset provided by Zeb Consultancy. Within the Notebook the data is foremost described and explained and then the most significant issues are presented. 

Once the issues are clearly stated, the features and their respective distributions are graphed for the reader to better understand the data types, characteristics and statistics.

## Data Transformation

This section is devoted to the transformation of the dataset prior to the data modelling. Within this section, two Notebooks are present:

  - *Data Transformation*
  - *Web Scraping*.

The former Notebook wants to transform the features which presented issues in the *Data Mining* Notebook. Precisely, it tackles missing/ zero values, it corrects skewed distributions and further normalises and standardises the dataset. Lastly, the Notebook also separates the dataset into two new datasets. By doing so, the research can achieve greater accuracy and validity in later clustering.

The latter Notebook, on the other hand, utilises web-scraping techniques in order to collect more data. Specifically, it collects data from German postcodes to geographically segment the observations of the dataset.

## Data Modelling

The data modelling applies clustering techniques to the original datasets. The models applied are the following:

  - *K-Means*
  - *Hierarchical Clustering*
  - *K-Modes*
  - *DBSCAN*
  - *Fuzzy C-Means*
  - *Self Organizing Maps*.
 
 For the sake of readability, each modelling technique is reported and summarised within a new Notebook. 

## PCA Data Modelling

Within this section, the datasets are foremost dimensionally reduced through the application of Principal Component Analysis. Following the reduction of the datasets, data modelling techniques are once again applied to the datasets. The models applied are the following:

  - *K-Means*
  - *Hierarchical Clustering*
  - *K-Modes*
  - *DBSCAN*
  - *Fuzzy C-Means*
  - *Self Organizing Maps*.

For the sake of readability, each modelling technique is reported and summarised within a new Notebook.

## Cluster Explanation

This section selects the best models according to pre-defined performance metrics and reports the main findings, both visually and in written form.

## Granular Segmentation

This section was devoted to an excercise later deemed inefficient and redundant. Specifically, the research wanted to segment the datasets even further to then apply the clustering techniques. While this would have provided more granular results, the modelling was not aligned with the initial objective of the research and the clustering results did not prove as efficient as initially hoped for. Consequentially, the idea was dropped but the Notebook was kept as a reference.

## Extra Packages

This section contains a Notebook detailing extra modules and packages which were initially utilised within the research. At later stages the modules/ packages were deleted from the Notebooks but a historical record was kept within a Notebook. This Notebook is 'commented-out' since it was not used.
