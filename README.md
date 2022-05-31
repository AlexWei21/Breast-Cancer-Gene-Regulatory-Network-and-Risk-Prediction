# **Gene Regulatory Network and Cancer Prediction in Breast Cancer**

Contributors: Jinglun Li, Yidan Ma, Zhengkuan Tang, Ziming Wei

## Background

Breast Cancer is one of the most common cancers in the world. According to the National Breast Cancer Foundation, there was an estimated 281,550 new cases of invasive breast cancers in the U.S. in 2021, and an estimated number of 43,600 women died from breast cancer in the U.S. [1] The huge population of breast cancer is a huge driving force for breast cancer research both in dry lab and wet lab. Though there were already a lot of researches done in discovering the mechanism of breast cancer, most of them were conducted in the wet lab and couldn&#39;t completely explain the mechanism of breast cancer at a genomic level. Most of the therapeutics now are still through surgeries, and according to the Cancer Treatment Centers of America, leads to an average of 7 percent to 11 percent Recurrent Rate of Breast Cancer. [2] In order to decrease the rate of recurrence, we have to create a gene network and use machine learning algorithms to find out important target genes for possible gene therapies for Breast Cancer.

## Section Overview

- **Differential Gene Expression (DGE) Analysis**

In order to figure out the genes that are crucial for the development of breast cancer, we conducted a differential gene expression analysis. The analysis focused on finding out the genes that are differentially expressed between cancer samples and normal samples. The filtered out genes may indicate that they perform an important role in promoting or recessing the development of breast cancer.

- **Data Preprocessing and Gene Ontology Enrichment Analysis**

After identifying differentially expressed genes, Gene Ontology Enrichment Analysis was performed to find out the significant pathways to which the differentially expressed genes belong. The GO Enrichment Analysis could both help to validate the result of Differential Gene Expression Analysis and discover possible pathways for future gene therapies to target. The methods and visualizations for data preprocessing could be found in this module as well. Raw data was scaled, ID converted, and visualized to facilitate future analysis.

- **ML-Based Feature Selection and Predictive Model Construction**

After data pre-processing, a basic clustering algorithm is used to determine if the samples from the dataset are clustered into several categories. Then, several ML-based methods were applied to find out important genes that support the classification of breast cancer subtypes. After that, an ML-based prediction model was built on the selected genes to model the relationship between the gene expression level and different types of breast cancer.

- **Biological Network**

After getting two parallel sets of genes: differentially expressed genes and machine learning selected genes, top genes for each panel were analyzed in the network context. With appropriate threshold for nodes and edges, two main gene networks were constructed. Networks with breast cancer association information were visualized to represent the characteristics of two sets. Hubs were identified in both networks, where the common hubs were regarded as a main result of the whole project.
