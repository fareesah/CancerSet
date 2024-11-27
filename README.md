# Breast Cancer Classification Using Logistic Regression

## Project Overview
This project leverages the Wisconsin Breast Cancer Diagnostic Dataset to build a classification model that predicts whether a tumor is malignant or benign. The project demonstrates a complete end-to-end machine learning workflow, including data preprocessing, exploratory data analysis, model training, and feature selection.

## Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- **Description**: The dataset contains measurements derived from digitized images of breast mass fine needle aspirates (FNAs).
- **Features**: 30 numerical features describing cell nuclei characteristics (e.g., radius, texture, concavity).
- **Target**: Binary classification of tumors into:
    - M (Malignant)
    - B (Benign)

## Workflow
### 1. Exploratory Data Analysis (EDA)
- Visualized class distribution, feature correlations, and statistical summaries.

### 2. Data Preprocessing
- Handled missing values and irrelevant columns.
- Encoded the target variable and scaled features using StandardScaler.

### 3. Classification Model
- Built a Logistic Regression classifier achieving an accuracy of 97.08% on test data.

### 4. Feature Selection
- Identified top 10 influential features using Logistic Regression coefficients.

### 5. Reproducible Workflow
- Designed a modular and well-documented pipeline for analysis and model building.

## Technologies Used
- **Languages**: Python
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn

## Results
- **Model Performance**: Achieved a classification accuracy of 97.08% with Logistic Regression.
- **Top Features**: Identified significant features such as worst radius, worst texture, and mean concave points.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CancerSet.git
   cd CancerSet
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the pipeline:
   ```bash
   python breast_cancer_pipeline.py

## Key Insights
This project demonstrates practical skills in:
- Data preprocessing and feature scaling.
- Building and evaluating classification models.
- Extracting and interpreting feature importance.

## Next Steps
- Experiment with other classification models (e.g., Random Forest, SVM).
- Perform hyperparameter optimization for improved performance.
- Add explainability methods such as SHAP or LIME.

