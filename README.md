# Predicting Future User Connections in Social Networks with Machine Learning Techniques

This repository contains the source code, implementation, and research documentation for my BSc Thesis project at the **World University of Bangladesh (WUB)**.

## 📌 Project Overview
Predicting future connections in social networks is crucial for friend recommendations, security threat detection, and personalized user experiences. This research proposes a hybrid approach combining traditional topological features (e.g., Common Neighbors, Shortest Path) with non-topological/behavioral features (e.g., User Activity, Interests, Demographics).

## 👥 Authors
- **P. M. Niamul Hasan** (ID: 03/22/60/3563)
- **Supervisor:** MD. Mahedi Hassan, Lecturer, Dept. of CSE, WUB

## ⚙️ Key Highlights & Results
- **Dataset:** Facebook dataset (21 features, 2,997 instances) with SMOTE data balancing.
- **Algorithms Explored:** Random Forest, SVM, k-NN, XGBoost, Ensemble Models (Voting, Stacking, Bagging, AdaBoost, Gradient Boosting), and Deep Learning (Keras DNN, Transformer, MLP).
- **Best Model:** **Keras DNN** achieved the highest accuracy of **92.80%** and an **AUC of 0.9863**.
- **Explainable AI (XAI):** Integrated **SHAP** analysis to interpret feature importance, revealing `shortest_path` and `same_community` as primary decision drivers.

## 📂 Repository Contents
- `Link-Prediction Niamul.ipynb`: Google Colab notebook containing complete code, model training, evaluation, and output visualizations.
- `Thesis-Paper.pdf`: The complete formal thesis report.

## 🚀 How to View
You can browse the `.ipynb` file directly on GitHub with its executed outputs or download it to run in Google Colab!
