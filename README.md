# Classical_ML

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-Classical-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Framework-scikit--learn-orange?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
</p>

<p align="center">
A collection of classical machine learning implementations and end‑to‑end ML workflows for learning, experimentation, and research.
</p>

---

## Overview

**Classical_ML** is a repository dedicated to implementing and exploring classical machine learning algorithms.  
It demonstrates the full machine learning pipeline — from **data preprocessing and feature engineering** to **model training, evaluation, and visualization**.

The project focuses on:

- Implementations **from scratch** for deeper understanding
- **scikit‑learn** implementations for comparison
- Clean and reproducible **Jupyter notebooks**
- Clear visualizations and evaluation metrics

---

## Repository Structure

```
- **Classification**:
  - Decision_Tree/
  - KNN/
  - Naive_Bayes/
  - Logistic_Regression/
  - SVM/

- **Regression**:
  - Linear_Regression/
  - Polynomial_Regression/

- **Clustering**:
  - DBSCAN
  - K-means
  - segmentation
  - img/

- **datasets**: Stores various datasets used for training and testing models.

- **requirements.txt**: Lists all the Python dependencies required to run the code in this repository.

- **README.md**: This file, providing an overview of the repository.
```

Each notebook represents an independent mini‑project and can be executed separately.

---

## Implemented Algorithms

### Classification

| Algorithm | Implementation | Dataset |
|---|---|---|
| Decision Tree | From Scratch | `make_blobs` |
| K‑Nearest Neighbors | From Scratch | `make_blobs` |
| Naive Bayes | From Scratch | Synthetic Data |
| Logistic Regression | Scratch / sklearn | Breast Cancer |
| Support Vector Machine | sklearn | Iris |

### Regression

| Algorithm | Implementation |
|---|---|
| Linear Regression | From Scratch |
| Polynomial Regression | From Scratch |

### Clustering

| Algorithm | Implementation |
|---|---|
| DBSCAN | From Scratch / sklearn |
| K-means | From Scratch / sklearn |
| Segmentation | Example implementations |

---

## Machine Learning Workflow

Typical workflow followed in the notebooks:

1. Data Loading or Generation  
2. Data Cleaning  
3. Feature Scaling  
4. Train / Test Split  
5. Cross‑Validation  
6. Hyperparameter Tuning  
7. Model Training  
8. Model Evaluation  
9. Visualization  

---

## Evaluation Metrics

| Task | Metrics |
|---|---|
| Classification | Accuracy, Confusion Matrix, ROC Curve, AUC |
| Regression | Mean Squared Error (MSE), R² Score |
| Clustering | Silhouette Score, Davies-Bouldin Index (To be added) |

---

## Visualizations

The repository includes multiple visualizations to better understand model behavior:

- Decision boundaries  
- Confusion matrices  
- ROC curves  
- Regression lines  
- Actual vs Predicted comparisons  
- Cluster visualizations (For Clustering algorithms)

Libraries used:

- matplotlib  
- seaborn  

---

## Installation

Clone the repository and install dependencies:

```
git clone https://github.com/ML-Labratories/Classical_ML.git
cd Classical_ML
pip install -r requirements.txt
```

---

## Dependencies

| Library | Purpose |
|---|---|
| NumPy | Numerical computation |
| Pandas | Data manipulation |
| scikit-learn | Machine learning utilities |
| Matplotlib | Visualization |
| Seaborn | Statistical visualization |

---

## Usage

Run Jupyter Notebook:

```
jupyter notebook
```

Open any notebook and execute the cells.

All notebooks are **independent and self‑contained**.

---

## Future Improvements

Planned extensions include:

- Clustering algorithms (Further development and more datasets)
- Ensemble learning methods
- More benchmark datasets
- Additional visualizations
- Experiment tracking

---

## Contributing

Contributions are welcome.

You can contribute by:

- Implementing new machine learning algorithms
- Improving existing implementations
- Adding datasets or experiments
- Improving documentation
- Fixing bugs

Steps:

1. Fork the repository  
2. Create a new branch  
3. Make your changes  
4. Submit a Pull Request  

You can also open an **Issue** for suggestions or bug reports.

---

## License

License information will be added in a future update.

---

## Maintainers

Maintained by the **ML‑Labratories** organization.


