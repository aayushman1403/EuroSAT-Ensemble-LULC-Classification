# 🛰️ EuroSAT-Ensemble-LULC-Classification

> **Project Description:** Ensemble Learning project for Land Use/Land Cover (LULC) classification on the EuroSAT 13-band spectral dataset, comparing Random Forest and XGBoost performance.

## 💡 Project Overview

This project implements and evaluates advanced **Ensemble Learning** techniques to classify **Land Use and Land Cover (LULC)** types using the full **13-band multispectral features** of the EuroSAT satellite imagery benchmark. The goal is to demonstrate how ensemble methods—specifically **Bagging** and **Boosting**—significantly improve classification accuracy and robustness over a single baseline classifier (Decision Tree) in a real-world remote sensing context.

The project uses feature engineering to convert raw TIF spectral data into a tabular format, making it highly efficient for non-GPU execution.

---

## 🛠️ Technologies and Requirements

This project is built using standard data science and machine learning libraries.

### Prerequisites
* Python 3.8+
* Google Colab or Jupyter Notebook (recommended for easy data access)

### Required Libraries
The entire environment can be set up using pip:

```bash
pip install pandas numpy scikit-learn xgboost rasterio matplotlib seaborn tqdm
