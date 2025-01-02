# Global Development Measurement

This project focuses on clustering global development metrics. The goal is to identify patterns and group similar countries based on various development indicators.

## Project Overview

- **Exploratory Data Analysis (EDA)**: Conducted to understand the data distribution and relationships between variables.
- **Clustering Algorithms Applied**:
    - KMeans
    - Agglomerative Clustering
    - DBSCAN
- **Model Selection**: KMeans was chosen for the final model as it provided the highest silhouette score, indicating better-defined clusters.

## Deployment

The final model was deployed using Streamlit, allowing for an interactive web application to visualize and explore the clustering results.

## How to Run

1. Clone the repository.
2. Install the required dependencies.
3. Run the Streamlit application.

```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
streamlit run app.py
```

## Results

The KMeans clustering model successfully grouped countries into distinct clusters, providing insights into global development patterns.

## Conclusion

This project demonstrates the use of clustering techniques to analyze global development metrics, with KMeans providing the best performance based on silhouette scores.
