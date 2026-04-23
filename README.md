# High-Dimensional Image Clustering: PCA & Agglomerative Clustering

## Overview
This project tackles the "Curse of Dimensionality" in Machine Learning by applying advanced unsupervised learning techniques to cluster high-dimensional image data (Handwritten Digits). The pipeline successfully groups unlabeled images into 10 distinct clusters representing the digits 0-9.

## Key Technical Achievements
1. **Dimensionality Reduction (PCA):**
   - Processed raw image datasets containing 784 pixel-features per image.
   - Applied Principal Component Analysis (PCA) to extract the most critical features.
   - Mathematically determined the optimal number of components (132) required to retain **95% of the cumulative variance**, drastically reducing computational complexity while preserving essential spatial data.
2. **Hierarchical Clustering:**
   - Implemented **Agglomerative Clustering** (a bottom-up hierarchical approach).
   - Utilized Euclidean distance and `Ward` linkage to minimize the variance within each cluster, effectively grouping the reduced data into 10 distinct digit classes.
3. **Competitive Benchmarking:**
   - The model's clustering performance was evaluated and ranked on a competitive leaderboard, demonstrating high accuracy in grouping unlabeled visual data.

## Technologies Used
- Python
- Scikit-Learn (`PCA`, `AgglomerativeClustering`)
- Pandas & NumPy (Linear Algebra and Data Manipulation)
- Unsupervised Learning & Computer Vision
