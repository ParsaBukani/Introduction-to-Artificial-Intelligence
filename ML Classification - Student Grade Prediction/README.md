# Student Performance Prediction — Machine Learning Classification

_Intro to Artificial Intelligence — University of Tehran_

This project builds **machine learning classifiers** to predict students’ **final AI course grade** from demographic, social, and academic features. The workflow covers **data preprocessing & feature engineering**, **model development** (library models and a **Decision Tree from scratch**), **hyperparameter tuning**, and **evaluation** with multi-class metrics.


## Tasks

1. **Data & Targets**
   - Use the provided student dataset (demographics, study habits, prior grades, etc.).
   - Convert `finalGrade` (0–20) to four classes:  
     - **A:** ≥ 17  
     - **B:** 14–16  
     - **C:** 10–13  
     - **Fail:** < 10  

2. **Preprocessing & Feature Engineering**
   - Handle missing values (try at least **3** reasonable imputation strategies).  
   - Drop/derive columns where appropriate; convert categorical fields to numeric.  
   - Optional transforms (e.g., log scaling, feature combinations) when beneficial.  

3. **Train/Test Protocol**
   - Split data into **80% training** and **20% testing**.  
   - Apply **normalization/standardization** where required (fit on train, apply to test).  

4. **Models (Scikit-Learn & XGBoost)**
   - **Naive Bayes**  
   - **Decision Tree**  
   - **Random Forest** (tune with **RandomizedSearchCV**)  
   - **XGBoost** (tune key hyperparameters with **GridSearchCV**)  

5. **Decision Tree — From Scratch**
   - Implement a custom `DecisionTree` with:  
     - `__init__(max_depth=...)`  
     - `fit(X, y)` using **entropy** and information gain  
     - `predict(X)` via tree traversal / majority vote at leaves  
   - **Compare** against the sklearn implementation.

6. **Evaluation & Reporting**
   - Report metrics: **Accuracy, Precision, Recall, F1**, **Confusion Matrix**, and **macro/micro/weighted** averages.  
   - Analyze preprocessing choices, model trade-offs, tuning effects, and runtime.  
   - *(Optional)* Feed your own profile to the best model and record the predicted grade class.  


## License

This project is licensed under the **MIT License**.


## Acknowledgements

Developed under the supervision of **Dr. Fadaei** and **Dr. Yaghoubzadeh**  
Designed by **Javad Kavian, Mohammad Amanlou, Mahdi Naeini**

