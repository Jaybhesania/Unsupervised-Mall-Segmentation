# ANN-Based Customer Segmentation

## Project Overview

This project leverages **Artificial Neural Networks (ANN)** and **Autoencoders** to perform advanced **customer segmentation** and **churn prediction** using historical sales data. Through **dimensionality reduction**, and **KMeans clustering**, it provide actionable insights for marketing and sales optimization.

### Key Highlights

* **Sales Data Preprocessing & EDA**: Cleaned and visualized insights from raw sales data.
* **Feature Engineering**: Categorical encoding, normalization, and transformation.
* **Unsupervised Clustering**: KMeans applied on scaled data and encoded features.
* **Autoencoder Model**: Trained deep autoencoder for nonlinear dimensionality reduction.
* **3D/2D PCA Visualization**: Interactive clustering views with Plotly.

## Tech Stack

* **Languages**: Python
* **ML Libraries**: TensorFlow, Keras, scikit-learn, opencv-python
* **Visualization**: Plotly, Matplotlib, Seaborn
* **Data**: [Kaggle Sales Dataset](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)

## Project Structure

```
.
├── sales_data_sample.csv      # Raw dataset
├── autoencoder.h5             # Saved ANN model
├── AI_in_Marketing.ipynb      # Notebook for preprocessing, modeling & clustering
├── README.md                  # This file
```


* Explore customer segments
* Visualize sales clusters in 2D/3D
* Understand key drivers of churn

## Getting Started

1. Install dependencies:

   ```bash
   pip install tensorflow scikit-learn opencv-python plotly
   ```

3. Upload `sales_data_sample.csv` and enjoy the insights!

## Contributions & Credits

* Dataset: [Kaggle - Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)
