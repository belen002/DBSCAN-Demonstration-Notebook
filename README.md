# DBSCAN-Demonstration-Notebook

# Description

# This notebook demonstrates the DBSCAN (Density-Based Spatial Clustering of Applications with Noise) algorithm and compares it with K-Means clustering using a non-linear dataset. The goal is to show how DBSCAN successfully identifies arbitrarily shaped clusters and noise points, where K-Means fails due to its assumption of spherical clusters.

# Objective

# To demonstrate the working principles and advantages of DBSCAN over K-Means on non-spherical data using visual comparison.

# Dataset

# Dataset: make_moons

# Samples: 300

# Noise: 0.05

# Reason: The moon-shaped structure highlights the limitations of K-Means and the strengths of DBSCAN.

# Methods Used

#

How to Run
pip install numpy matplotlib scikit-learn
Run the notebook cells in order to reproduce the results.

Conclusion

DBSCAN is a powerful density-based clustering algorithm suitable for datasets with complex structures and noise, making it a strong alternative to K-Means in real-world scenarios.
