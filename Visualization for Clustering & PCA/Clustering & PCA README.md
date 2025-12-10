# Data Visualization for Clustering and PCA

## **Project Summary**

This project involves performing a **Cluster Analysis** and a **Principal Components Analysis (PCA)** on the **Angry Birds (Cardinal Personalities).xlsx** dataset. The dataset models personality types of northern cardinals from different environments, with three predefined personality groups.

The goal is to:

* Explore dimensionality in the dataset.
* Compare clusters derived from k-means with the original personality groupings.
* Visualize the relationship between raw data, clusters, and PCA components.

---

## **1. Data Preparation and Analysis**

* Data cleaned and structured for clustering and PCA.
* K-means clustering run with **3 groups**.
* PCA applied to the same dataset to reduce dimensionality and visualize separation along principal components.
* Variables standardized if necessary to avoid scale bias in clustering and PCA.

---

## **2. Cluster Plot**

* Constructed a cluster plot showing the three k-means clusters in relation to the original personality groups.
* Plot uses appropriate scatterplots or multi-panel layout to show separation across multiple variables.
* Variable names cleaned, axes informative, no data artifacts, and legible font sizes.
* Caption clearly explains cluster alignment with the original personality groups, highlights variables contributing most to separation, and notes any overlap or misclassification.

---

## **3. PCA Plot**

* PCA plot shows cluster assignments along the first few principal component axes.
* Multi-panel layout used if necessary (e.g., PC1 vs PC2, PC1 vs PC3).
* Plot designed to visualize whether clusters and original personality groupings align along principal components.
* No data artifacts; axes labeled clearly, legend included, fonts and sizes legible.
* Caption describes which PCs contribute most to separation and how the PCA compares with cluster assignments.

---

## **4. Interpretation**

* Brief analysis comparing k-means clusters and PCA results with original personality groupings.
* Identifies which variables most strongly separate clusters.
* Notes consistencies and discrepancies between PCA, clusters, and the predefined personality groups.
* Interpretation concise and focused on main insights.

---

## **5. Code and Reproducibility**

* All steps, including data cleaning, clustering, PCA, and plotting, are reproducible.
* .ipynb file includes Cluster Plot first, PCA Plot second, Interpretation third, and the code at the end.

-----

# ***Summary of Findings***

***1: Clusters vs Personality Groups***
* Clusters produced by k-means show partial alignment with personality groups.
* This suggests that while k-means captures some relevant dimensions, it emphasizes variables differently than personality grouping.

***2: Key Variables***
* Cluster Analysis: Physical traits like Weight, WingL, and TarsusL are influential based on cluster centroids.
* Personality Groups: Behavioral traits like Exploration, Neophilia, and Boldness are more relevant to the personality column.

***3: PCA Alignment***
* PCA reveals moderate alignment with clusters and some alignment with personality groups.
* PC1 and PC2 (driven by traits like Weight and Exploration) show partial separation of clusters and personalities, but overlap remains for certain groups.
