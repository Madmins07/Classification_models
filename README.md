<div align="center">
  <img src="assets/banner.svg" alt="Classification Models. Titanic survival across seven classifiers, plus an SVM baseline on Iris." width="100%"/>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/jupyter-notebook-A6BDAD?style=flat-square&labelColor=0B0E0D&logo=jupyter&logoColor=EEF1ED" alt="jupyter notebook"/>
  <img src="https://img.shields.io/github/last-commit/Madmins07/Classification_models?style=flat-square&labelColor=0B0E0D&color=788A7F&label=updated" alt="last-commit"/>
  <img src="https://img.shields.io/github/license/Madmins07/Classification_models?style=flat-square&labelColor=0B0E0D&color=5A6A60" alt="license"/>
</div>

## about

A survey of classifiers on the Kaggle **Titanic** problem, all through scikit-learn and XGBoost, so the comparison is
about the models and the feature cleaning rather than the plumbing. Plus a one-screen SVM baseline on Iris.

## notebooks

| notebook | what it does | open |
|:--|:--|:--|
| [`Titanic.ipynb`](Titanic.ipynb) | Cleaning and encoding, then logistic regression, naive Bayes, KNN, SVM, decision tree, random forest and XGBoost, with accuracy and F1 for each. | <a href="https://colab.research.google.com/github/Madmins07/Classification_models/blob/main/Titanic.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/></a> |
| [`SVM_scikit.ipynb`](SVM_scikit.ipynb) | Support vector classifier on Iris with accuracy and micro-F1. | <a href="https://colab.research.google.com/github/Madmins07/Classification_models/blob/main/SVM_scikit.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/></a> |

## data

`Titanic.ipynb` expects the Kaggle files (`train.csv`, `test.csv`, `gender_submission.csv`) next to it; get them from
[kaggle.com/c/titanic](https://www.kaggle.com/c/titanic/data). Iris ships with scikit-learn.

---

<div align="center">
  <sub>Part of <a href="https://github.com/Madmins07">Madmins07</a> · Madhav Agarwal · IIT Kharagpur</sub>
</div>
