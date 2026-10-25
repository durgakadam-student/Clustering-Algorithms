# Clustering Algorithms

## Problem Statement
Implement clustering algorithms on a real-world dataset to identify meaningful groups within the data. Evaluate clustering quality using Silhouette Score, Davies–Bouldin Index, and visual inspection.

## Algorithms Implemented
- K-Means Clustering
- Agglomerative Clustering

## Dataset
The Wine Recognition dataset from Scikit-learn, containing 178 samples and 13 numerical features.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- PCA for visualization

## Evaluation Metrics
- **Silhouette Score:** Higher values generally indicate better-defined clusters.
- **Davies–Bouldin Index:** Lower values generally indicate better clustering.

## How to Run

Install the required libraries:

```bash
pip install scikit-learn pandas numpy matplotlib
```

Run the Python program:

```bash
python clustering_algorithms.py
```

## Results

| Algorithm | Silhouette Score | Davies–Bouldin Index |
|---|---:|---:|
| K-Means | 0.2849 | 1.3892 |
| Agglomerative | 0.2774 | 1.4186 |

K-Means performed slightly better on both evaluation metrics in this experiment.

## Author
Durga Kadam
