# Hill and Valley Prediction using Logistic Regression

## Project Overview
This project implements a **binary classification model** to predict whether a given terrain pattern forms a **hill (1) or a valley (0)** based on a dataset of 100 sequential points. The model uses **Logistic Regression** to classify the terrain.

## Dataset
- The dataset consists of **100 numerical features** representing X-values of terrain points.
- The **target variable** (Class) is **binary**:
  - `0`: Valley
  - `1`: Hill
- The dataset is sourced from [YBI Foundation](https://github.com/YBIFoundation/Dataset/raw/main/Hill%20Valley%20Dataset.csv).

## Data Preprocessing
- **Checked for missing values** and handled any inconsistencies.
- **Feature Scaling**: Standardized the feature set for better model performance.
- **Train-Test Split**: 80% training, 20% testing.

## Model Implementation
- Implemented a **Logistic Regression** model using **Scikit-learn**.
- **Confusion Matrix & Classification Report** were used to evaluate performance.

## Results & Performance
- **Accuracy:** ~75-85%
- **Precision & Recall:** Balanced performance across both classes.
- **Misclassification Rate:** Approximately 15-25%.

## Technologies Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)**
- **Jupyter Notebook** for development and visualization.

## How to Run the Project
1. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Download the dataset from the provided link.
3. Run the **Hill_And_Valley_Prediction_with_logistics.ipynb** notebook.
