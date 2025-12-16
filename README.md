# Iris Classification using KNN (KD-Tree)

## Overview
This task solves the **Iris flower classification** problem using the **K-Nearest Neighbors (KNN)** algorithm. A **KD-Tree** is used internally to optimize nearest-neighbor searches and improve performance.

## Dataset
- **Dataset:** Iris Dataset
- **Classes:** Setosa, Versicolor, Virginica
- **Features:** Sepal length, sepal width, petal length, petal width

## Methodology
- The dataset is split into **70% training** and **30% testing** data.
- Samples are selected **randomly without replacement**.
- **Class balance** is maintained using stratified splitting.
- A **KNN classifier** is trained using the KD-Tree search method.

## Evaluation
Model performance is evaluated using:
- **Confusion Matrix**
- **Precision**
- **Recall**
- **F1-score**

These metrics provide a clear assessment of classification performance for each Iris class.

## Outcome
The KNN model with KD-Tree efficiently classifies the Iris dataset and achieves strong performance across all evaluation metrics.
