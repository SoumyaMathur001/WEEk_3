# WEEk_3


# Stage 3: Model Development and Evaluation

## 📌 Introduction

This notebook focuses on building and evaluating a machine learning model to predict carbon emissions. It builds upon earlier stages by performing advanced feature selection and model tuning. The dataset originates from reliable open sources, and the goal is to build a well-performing, generalizable model.

## ⚙️ Notebook Setup

* Imported necessary Python libraries such as `pandas`, `numpy`, `scikit-learn`, and `matplotlib`.
* Set seeds and configured randomness controls to ensure reproducibility of results.

## 📊 Data Overview

* Provided an overview of the dataset including the shape, types of variables, and basic statistics.
* Reviewed missing values and data imbalances.

## 🏷️ Feature/Column Abbreviations

* Included a dictionary of abbreviations and units used for each column to improve interpretability.

## 🧪 Hypothesis

* **Hypothesis**: Certain measurable features (e.g., fuel consumption, engine size) significantly influence the level of carbon emissions.

## 🔍 Variable Selection

* Identified the **dependent variable**: `CO2 Emissions`
* Selected appropriate **independent variables** after initial correlation checks and domain knowledge.

## 🔀 Data Splitting

* Split the dataset into training and testing subsets (e.g., 80:20 ratio) to assess generalization ability.

## 🎯 Feature Selection

* Applied **Recursive Feature Elimination (RFE)** combined with **cross-validation** to retain the most relevant features and reduce dimensionality.

## 🧠 Model Building

* Chose **Random Forest Regressor** due to its robustness and ability to handle non-linear relationships.

## 🔧 Hyperparameter Tuning

* Performed **Grid Search CV** for hyperparameter tuning, evaluating combinations with cross-validation to find the best-performing model.

## 📈 Model Training & Evaluation

* Trained the tuned model using **cross-validation** on the training set.
* Assessed performance using metrics like R², RMSE, and MAE.

## 🧪 Test Set Validation

* Validated the final model on the **previously unseen test subset** to check for overfitting and real-world performance.

## 🧾 Conclusions

* Highlighted insights from the model performance.
* Validated the model's ability to generalize on unseen data.
* Documented challenges, limitations, and next steps for future improvement.

