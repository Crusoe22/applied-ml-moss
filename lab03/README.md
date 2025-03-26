# Predicting Titanic Survival Using Machine Learning

Overview
This project explores the Titanic dataset from Seaborn, applying different machine learning models to predict passenger survival. The goal is to compare model performance and understand how each algorithm interprets the data.


Each model is evaluated based on accuracy, precision, recall, and F1-score to determine the most effective approach for predicting survival. 🚢

### Results

| Model Type | Case | Features Used | Accuracy | Precision | Recall | F1-Score | Notes |
|------------|------|---------------|----------|-----------|--------|-----------|-------|
| **Decision Tree** | Case 1 | alone | 63% | 64% | 63% | 63% | - |
|                   | Case 2 | age | 61% | 58% | 61% | 55% | - |
|                   | Case 3 | age + family_size | 59% | 57% | 59% | 57% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **SVM (RBF Kernel)** | Case 1 | alone | 63% | 64% | 63% | 63% | - |
|                    | Case 2 | age | 63% | 66% | 63% | 52% | - |
|                    | Case 3 | age + family_size | 63% | 66% | 63% | 52% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **SVM (Linear Kernel)** | Case 1 | alone | 63% | 64% | 63% | 63% | - |
|                    | Case 2 | age | 63% | 66% | 63% | 52% | - |
|                    | Case 3 | age + family_size | 63% | 66% | 63% | 52% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **SVM (Poly Kernel)** | Case 1 | alone | 63% | 64% | 63% | 63% | - |
|                    | Case 2 | age | 63% | 66% | 63% | 52% | - |
|                    | Case 3 | age + family_size | 63% | 66% | 63% | 52% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **SVM (Sigmoid Kernel)** | Case 1 | alone | 63% | 64% | 63% | 63% | - |
|                    | Case 2 | age | 63% | 66% | 63% | 52% | - |
|                    | Case 3 | age + family_size | 63% | 66% | 63% | 52% | - |
|-------------------|------|---------------|----------|-----------|--------|-----------|-------|
| **Neural Network (MLP)** | Case 1 | alone | 63% | 64% | 63% | 63% | - |
|                    | Case 2 | age | 63% | 64% | 63% | 63% | - |
|                    | Case 3 | age + family_size | 63% | 64% | 63% | 63% | - |