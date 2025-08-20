# Speed Dating Classification

## Project Overview
This project explores the factors that influence romantic interest in a speed dating context.  
The target variable is the **partner’s decision** (yes/no) towards the subject.  

We apply and compare multiple classification algorithms to identify which features best predict romantic interest, with a focus on both **predictive performance** and **interpretability**.

---

## Objectives
- Understand which personal and interaction-based factors drive romantic interest.  
- Compare a range of classification models.  
- Evaluate models on accuracy, precision, recall, F1, and PR AUC to account for potential class imbalance.  
- Provide interpretable results supported by feature importance and visualization.  

---

## Dataset
- **Source**:  https://www.openml.org/search?type=data&sort=version&status=any&order=asc&exact_name=SpeedDating&id=40536
- **Target Variable**: Partner’s decision (binary: yes/no)  
- **Features**: Demographics, interests, and subjective ratings collected during the speed dating event.  

---

## Methods
The following classifiers will be implemented and compared:

- Decision Tree  
- Random Forest  
- Gradient Boosted Trees (XGBoost / LightGBM / CatBoost)  
- Logistic Regression  
- Support Vector Machines (SVM)  
- k-Nearest Neighbours (kNN)  
- Naïve Bayes  
- Linear Discriminant Analysis (LDA)  
- Neural Networks (MLP)  
- Ensemble Methods (Voting, Stacking)  

---

## Evaluation Metrics
- Accuracy  
- Precision, Recall, F1-score  
- ROC AUC  
- Precision-Recall AUC  
- Confusion Matrix  
- Geometric Mean for imbalanced datasets  

---

## Repository Structure
speed-dating-classification/
│
├── data/ <- Raw and processed data
├── notebooks/ <- Jupyter/R notebooks for exploration
├── src/ <- Scripts (cleaning, feature engineering, modeling)
├── reports/ <- Generated reports, figures, results
├── requirements.txt <- Dependencies
├── environment.yml <- For conda
├── README.md <- Project overview
├── .gitignore

## License
All rights reserved. For academic use only


