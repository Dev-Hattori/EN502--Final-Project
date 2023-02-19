
# Non-Blackbox Disease Prediction Model

## Problem Statement:
The dataset consists of 132
predictors/features using which
42 different types of diseases can
be predicted.
All of the 132 predictors have
Boolean type values for the
symptoms experienced by the
patient.

## Objective
Based on the dataset the aim of this project is to create and compare
several classification models for predicting the disease on the basis of
significant symptoms experienced by the patient.
The major reason why machine learning or deep learning model
aren’t widely used in the health-care industry is owing to the fact that
a layman cannot really explain the result of the model.
The main aim of the project is to finally train a few models that has a high
level of predictive performance without being a Blackbox model or
sacrificing interpretability.

## Methodology
**Decision Trees** are one of themost prominently used models in order to implement explainable predictive algorithms. But this interpretability comes at the cost of predictive performance.

In order to tackle this issue, we can perform **ensembling** of several Decision Trees in order to retain the interpretability of the model without sacrificing the prediction accuracy.

Ensembling is basically a version of **Wisdom of the Crowd** of Machine Learning models. 

In machine learning, an ensemble is a *collection of models whose predictions are averaged (or aggregated in some way)*. If the ensemble models are different enough without being too bad individually, the quality of the ensemble is generally better than the quality of each of the individual models. An ensemble requires more training and inference time than a single model.

Informally, for an ensemble to work best, the individual models should be independent. As an illustration, an ensemble composed of 10 of the exact same models (that is, not independent at all) won't be better than the individual model. On the other hand, forcing models to be independent could mean making them worse. Effective ensembling requires finding the balance between model independence and the quality of its sub-models.

## Models Trained
### CART (Classification And Regression Trees) Model
This is a simple Decision Tree that by default is set for classification task.
