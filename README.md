# Titanic Survival Analysis

This project analyzes the Titanic dataset from Kaggle to explore factors influencing passenger survival rates using data science and machine learning techniques.

## 📌 Project Overview
The analysis focuses on:
- Data preprocessing and cleaning
- Exploratory data analysis (EDA)
- Feature engineering
- Model training and evaluation
- Hyperparameter tuning and model optimization
- Comparing multiple machine learning models

## 📂 Files
- `KaggleTitanicAnalysis.ipynb`: Jupyter Notebook containing the full analysis and model development.
- `README.md`: Documentation for the project.

## 🔧 Requirements
To run this project, install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 📊 Exploratory Data Analysis (EDA)
Key aspects of EDA include:
- Handling missing values in features like `Age`, `Cabin`, and `Embarked`
- Analyzing survival rates based on different attributes such as gender, passenger class, age groups, and family size
- Visualizing trends and correlations using histograms, boxplots, and bar charts

## 🔍 Feature Engineering
Several new features are created to enhance model performance, such as:
- Extracting titles from passenger names
- Creating a `FamilySize` feature
- Categorizing `Age` and `Fare` into bins
- Encoding categorical variables (e.g., `Sex`, `Embarked`) using one-hot encoding

## 🤖 Machine Learning Models
The project explores and evaluates different classification models, including:
- **Logistic Regression**
- **Decision Trees**
- **Random Forest**
- **Support Vector Machines (SVM)**
- **Gradient Boosting (XGBoost, LightGBM, CatBoost)**

## 📈 Model Evaluation and Optimization
- Models are evaluated using **accuracy**, **precision**, **recall**, and **F1-score**.
- **Cross-validation** is applied to improve generalization.
- **Grid search** and **Randomized search** are used for hyperparameter tuning.

## 🚀 Running the Notebook
1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook KaggleTitanicAnalysis.ipynb
   ```

2. Run the cells step by step to see the data processing, visualizations, and model results.

## 📌 Results and Findings
- The project identifies key features influencing survival, such as **gender** and **passenger class**.
- **Feature engineering** improves model performance significantly.
- The **best-performing model** is determined based on cross-validation results and test set performance.

## 📜 License
This project is for **educational purposes** and follows an **open-source** license.

---

Happy Coding! 🚢
