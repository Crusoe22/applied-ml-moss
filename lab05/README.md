# ml-05

## Introduction

In this project, I explore a dataset of red wine physicochemical properties and their associated quality ratings, with the goal of building a machine learning model that can accurately predict **wine quality** based on chemical attributes.

This project showcases:
- Feature engineering
- Model comparison and evaluation
- Handling class imbalance
- Model tuning and justification

### Set up the virtual environment in the terminal:
``` shell
python3 -m venv .venv
```
Activate the virtual enivronment
``` shell
source .venv/bin/activate
```

Install requirements
``` shell
py -m pip install -r requirements.txt
```


Performance Metrics

We will evaluate model performance using the following metrics:

Accuracy –  The proportion of all predictions that are correct.
Precision – Proportion of positive predictions that are truly positive.
Recall – Proportion of actual positives that are correctly predicted.
F1 Score – Harmonic mean of precision and recall, balancing both.


Good models have:

High Test Accuracy – the model predicts well on new, unseen (e.g., test) data.
High Test F1 Score – especially useful  if some classes (categories) have fewer examples than others.
Small Gap between Train and Test accuracy – shows the model is generalizing well (not overfitting or underfitting).
Small Gap between Train and Test F1 score – shows the model is generalizing well (not overfitting or underfitting).