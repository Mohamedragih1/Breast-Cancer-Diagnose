# Breast cancer diagnose 

## Overview

This repository contains the implementation of dimensionality reduction using PCA and unsupervised clustering through K-Means on the Breast Cancer Wisconsin (Diagnostic) dataset. The assignment aims to explore the impact of dimensionality reduction on clustering results.

## Assignment Objectives

- Introduce dimensionality reduction through PCA.
- Implement K-Means using NumPy.
- Implement PCA using NumPy.
- Evaluate the impact of dimensionality reduction on clustering results.

## Problem Statement

Given the Breast Cancer Wisconsin (Diagnostic) dataset, the goal is to perform unsupervised clustering to identify inherent patterns or groupings within the dataset. The dataset consists of features computed from digitized images of fine needle aspirates (FNAs) of breast masses to distinguish between malignant and benign tumors.

## Assignment Details and Requirements

1. Implement K-Means using NumPy.
2. Implement PCA using NumPy.
3. Conduct two experiments:
   - First experiment: Cluster the dataset using K-Means.
   - Second experiment: Apply PCA and then cluster the dataset using K-Means.
   - Ensure no labels are used in both experiments.
4. In both experiments:
   - Apply the elbow method to find the optimal number of k clusters.
   - Compare the sum of square errors/distances in both experiments.
   - Include notes for both experiments.
5. In the second experiment:
   - Experiment with different numbers of principal components.
   - Visualize the results and compare them with the original labels.

