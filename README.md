# Crypto Clustering Analysis

---

## Overview

This project applies K-Means clustering and Principal Component Analysis (PCA) to classify cryptocurrencies based on price fluctuations over different timeframes. The analysis includes data preprocessing, dimensionality reduction, clustering, and visualization to uncover meaningful patterns in the cryptocurrency market.

---

## Objectives

- Aggregate and normalize cryptocurrency price change data.
- Apply K-Means clustering to identify market segments.
- Use PCA to reduce dimensionality and optimize clustering.
- Visualize clustering results using scatter plots and elbow method analysis.
- Compare clustering results before and after PCA transformation.

---

## Project Steps

1. Data loading and preparation:
   - Load cryptocurrency market data from a CSV file.
   - Normalize the data using `StandardScaler` for consistency.

2. Clustering with K-Means:
   - Apply the elbow method to determine the optimal number of clusters.
   - Perform K-Means clustering on the original scaled data.

3. Dimensionality Reduction with PCA:
   - Reduce the dataset to three principal components.
   - Assess the explained variance of each component.

4. Optimized Clustering with PCA Data:
   - Apply K-Means clustering to the PCA-transformed data.
   - Compare cluster assignments before and after PCA.

5. Visualization and Insights:
   - Generate scatter plots to visualize clusters.
   - Interpret key features influencing each principal component.

---

## File Structure

- **Jupyter Notebook**: Contains the full clustering analysis, including visualizations and results.

- **Data Files**:
  - `crypto_market_data.csv` (Original dataset)

- **Output Files**:
  - `pca_transformed_data.csv` (PCA-reduced dataset)
  - `clustered_results.csv` (Cluster assignments)

---

## Data Source

This analysis uses cryptocurrency price change data. The dataset includes historical price fluctuations over multiple timeframes, sourced from a cryptocurrency market API.

---

## Results

The analysis successfully grouped cryptocurrencies into meaningful clusters based on price fluctuations. PCA helped optimize clustering by reducing dimensionality while retaining essential information.

---

## License

This project is licensed under the MIT License. See the LICENSE file in the repository for details.

