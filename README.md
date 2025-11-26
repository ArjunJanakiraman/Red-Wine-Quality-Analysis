# Red Wine Quality Prediction and Analysis

## Project Overview

This project analyzes the physicochemical properties of red wine to predict its quality. The goal is to develop and optimize a **Random Forest Classifier** that can accurately distinguish high-quality wines (score >= 7) from lower-quality wines (score <= 6).

The analysis demonstrates proficiency in the full machine learning pipeline, including: advanced feature engineering, systematic model comparison, hyperparameter tuning, and preparation of deployable assets.

## Key Results and Insights

* **Prediction Metric:** A high **Weighted F1-Score** was achieved, chosen specifically to address the class imbalance between high- and low-quality wines.

* **Feature Engineering:** Model performance was improved by creating domain-specific features, including **Total Acidity** and **Bound Sulphur Dioxide**.

* **Key Predictors:** Analysis identified **Alcohol Content** (strong positive predictor) and **Volatile Acidity** (strong negative predictor) as the most critical factors influencing wine quality.

* **Model Selection:** The **Random Forest Classifier** was selected over a **K-Nearest Neighbors (KNN)** baseline due to its superior performance in handling the complex, non-linear feature space.

## Repository Contents

| File | Purpose |
| :--- | :--- |
| `Red_Wine_Quality_Analysis.ipynb` | The complete, executed Jupyter Notebook containing all code, analysis, and visualizations. |
| `winequality-red.csv` | The raw dataset required to ensure project reproducibility. |
| `final_rf_classifier.joblib` | The final, optimized **Random Forest Classifier** saved for deployment. |
| `feature_scaler.joblib` | The fitted **`StandardScaler`** object, required for preprocessing new data inputs. |

## Run the Analysis

You can view or execute the complete analysis directly in Google Colab without any local setup:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](<Paste your direct Colab link here>)

## Technologies and Libraries

* **Language:** Python 3

* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, joblib
