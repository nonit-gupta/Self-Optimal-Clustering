# Self Optimal Clustering Technique using Optimized Threshold Function

This repository contains the implementation and results of our course project for **EE656: Artificial Intelligence, Machine Learning, Deep Learning and its Applications**, under the guidance of **Prof. Nishchal K. Verma**, Department of Electrical Engineering, IIT Kanpur.

## Project Overview

We implemented a novel **Self-Optimal Clustering (SOC)** algorithm, which builds upon the Improved Mountain Clustering (IMC) technique by introducing a mathematically optimized threshold function. The optimization is achieved through **Lagrange interpolation**, iteratively updating the clustering to maximize the **Global Silhouette Index (GSI)** and other validation metrics.

### Key Features
- Clustering based on potential fields and adaptive thresholds
- Optimization of threshold via interpolation to improve cluster quality
- Applied to **image segmentation** tasks involving synthetic and natural images
- Comparison with standard clustering methods (K-Means, FCM, EM, K-Medoids, IMC)
- Evaluation using multiple indices: GSI, Dunn Index (DI), Partition Index (PI), and Separation Index (SI)

### Files
- `self-optimal-clustering.ipynb`: Main implementation notebook with experiments and visualizations.
- `EE656_Project_Report.pdf`: Full technical report of the project.
- `SOC.pdf`: Presentation slides summarizing the method and results.
