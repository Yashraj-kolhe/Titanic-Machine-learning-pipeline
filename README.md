# Titanic Machine Learning Pipeline 🚢

## Project Overview
This repository contains a structured end-to-end Machine Learning pipeline to predict passenger survival on the Titanic. The goal of this project is to implement robust data preprocessing and classification using `scikit-learn` pipelines, moving away from messy, linear code toward scalable, production-ready machine learning practices.

## Current Status
Currently setting up the core data preprocessing architecture. 
* Data successfully loaded via Pandas.
* Initializing `ColumnTransformer` to handle missing values and categorical data simultaneously.

## Tech Stack & Tools
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** Pandas, NumPy, Scikit-Learn

## Repository Structure
* `ml-pipeline.ipynb`: The main Jupyter Notebook containing the code, data exploration, and the `scikit-learn` pipeline setup.
* `train.csv`: The training dataset containing passenger information (Age, Sex, Class, Fare, etc.) and survival outcomes.

## Next Steps
1. **Complete Preprocessing:** Implement `SimpleImputer` for handling missing age data and `OneHotEncoder` for categorical text features.
2. **Build the Pipeline:** Chain the `ColumnTransformer` directly into a `DecisionTreeClassifier`.
3. **Model Evaluation:** Split the data using `train_test_split` and evaluate the model's accuracy.
4. **Optimization:** Explore different algorithms and hyperparameter tuning to improve survival prediction.

---
*Developed as part of an ongoing journey into robust Machine Learning engineering and automation.*
