# Football Analysis Project  

**An end-to-end machine learning pipeline for analyzing football player positions using unsupervised clustering, dimensionality reduction, and supervised classification.**  

---

## Overview  
This project leverages machine learning to:  
1. **Cluster players** into positions (e.g., Defender, Midfielder, Forward) using unsupervised learning (K-means, DBSCAN).
2. **Investigate** hidden relationships and potential subgroups with Topological Data Analysis (Mapper Algorithm).
3. **Classify positions** using supervised models (Random Forest, Neural Networks).  
4. **Visualize player roles** with dimensionality reduction (PCA, UMAP).  

Key techniques:  
- **Unsupervised Learning**: Clustering (K-means, DBSCAN), Dimensionality Reduction (PCA, UMAP)  
- **Supervised Learning**: Random Forest, Neural Networks (PyTorch)  
- **Evaluation**: Confusion matrices, precision/recall, silhouette scores  

---

## Features  
### 1. Unsupervised Clustering  
- **K-means & DBSCAN**: Groups players based on performance metrics (e.g., tackles, passes, shots).  
- **PCA/t-SNE Visualization**: Reduces features to 2D/3D for interpretability.  

### 2. Supervised Classification  
- **Random Forest**: Predicts positions from player stats.  
- **Neural Network (PyTorch)**: Deep learning model for position classification.  

### 3. Performance Metrics  
- **Clustering**: Silhouette score, cluster purity.  
- **Classification**: Accuracy, F1-score, confusion matrices.

---

## 📂 Data  
This project uses the following public dataset:  
**Soccer Match Event Dataset**  
Pappalardo, L., & Massucco, E. (2019). *Soccer match event dataset*. figshare.  
DOI: [10.6084/m9.figshare.c.4415000.v5](https://doi.org/10.6084/m9.figshare.c.4415000.v5)  

---

## 🏆 Acknowledgments  
- Data sourced from Pappalardo et al.’s [Soccer Match Event Dataset](https://doi.org/10.6084/m9.figshare.c.4415000.v5).  
- Inspired by [optional: cite related papers or projects].  
