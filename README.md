# Mushroom Classification Analysis (Python)

## Overview
An applied machine learning analysis that evaluates and compares the performance of two classical classification models—**Decision Trees** and **Random Forests**. Using a dataset of 8,124 mushroom samples, the project classifies specimens as **edible** or **poisonous** based on categorical physical characteristics such as odor, cap shape, and habitat.

Rather than focusing solely on model performance, this project emphasizes understanding **why** these models behave as they do on this dataset through preprocessing choices and evaluation metrics.

## Features

- **Data Preprocessing**  
  Encodes 22 categorical features using label encoding to prepare the dataset for classification.

- **Binary Classification Task**  
  Predicts mushroom edibility with two target classes: Edible (`e`) and Poisonous (`p`).

- **Comparative Model Analysis**  
  Compares a **Decision Tree** (single-model, rule-based) against a **Random Forest** (ensemble-based) approach.

- **Model Evaluation**  
  Assesses performance using Accuracy, Precision, Recall, F1-score, and Confusion Matrices.

- **Exploratory Insights**  
  Analyzes feature importance and highlights potential overfitting and dataset bias.

## Technical Specifications

- **Language:** Python 3.x  
- **Libraries:** `scikit-learn`, `pandas`, `numpy`, `matplotlib`  
- **Platform:** Jupyter Notebook / Google Colab  

## Project Context
This project was developed as Major Course Output 3 (MCO3) for **CSINTSY – Introduction to Intelligent Systems** at De La Salle University.

It addresses the following learning outcomes:

- **LO4:** Experimenting with machine learning models for real-world classification tasks  
- **LO5:** Communicating technical analysis and results clearly through written documentation  

Although both models achieved 100% accuracy, the emphasis of this project is on **comparative analysis**—examining why tree-based models perform exceptionally well on this dataset and discussing the implications of highly predictive features.

## Analysis Highlights

- **Decision Tree Behavior**  
  The tree rapidly converges on highly discriminative features (e.g., odor), producing clear decision paths.

- **Random Forest Robustness**  
  Ensemble averaging reduces variance and confirms the stability of dominant predictive features.

- **Dataset Characteristics**  
  Certain attributes are strongly correlated with toxicity, enabling perfect classification and prompting discussion on dataset simplicity and generalization limits.

- **Critical Reflection**  
  The results illustrate how high accuracy does not always imply model complexity and reinforce the importance of understanding dataset structure when interpreting ML outcomes.
