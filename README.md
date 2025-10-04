# Application-of-Clustering-for-Partitioning-Forest-Trees-into-Representative-Sections
Comparative implementation of clustering algorithms (K-Means, DBSCAN, Hierarchical, Hybrid, KDE-based) for structured data partitioning and outlier detection.

This repository contains the implementation and analysis code for the paper “The Application of Clustering Algorithms for Partitioning Forest Trees into Representative Sections”, presented at the 6th International Conference on Soft Computing, Faculty of Technology and Engineering, East of Guilan, November 19–20, 2025.

The project explores and compares several clustering algorithms—K-Means, K-Means with local DBSCAN refinement, Agglomerative Hierarchical Clustering, Hybrid Hierarchical–DBSCAN Clustering, and Agglomerative Clustering with KDE-based Outlier Detection—on a structured spatial dataset.

The goal is to evaluate how different clustering paradigms handle non-spherical data distributions, noise identification, and structural representativeness. Each method is assessed through internal metrics (Silhouette, Davies–Bouldin, Calinski–Harabasz) and visual correspondence to reference heatmaps. Results show that the Agglomerative + KDE hybrid achieves the most consistent cluster delineation and statistically grounded outlier detection.

This repository includes Python implementations, evaluation scripts, and visualization utilities for reproducing all experimental results and comparative analyses presented in the paper.
