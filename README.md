# adaboost from scratch

This project implements AdaBoost from scratch on the Breast Cancer dataset.
We use DecisionTreeClassifier from the scikit-learn library as the weak learner to build individual trees and make predictions.
After each round, the sample weights are updated based on the misclassified instances, and a new tree is trained accordingly.
The optimal number of estimators is determined using cross-validation accuracy with cross_val_score and the AdaBoostClassifier from scikit-learn.
Finally, we compare the accuracy of our custom AdaBoost implementation with the built-in AdaBoostClassifier to evaluate performance.


## requirements
[python](https://www.python.org/downloads/)

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.

```bash
pip install numpy
pip install scikit-learn
```

## how to run
To run this Jupyter Notebook, you can either open it in Google Colab using the link below or run it locally using Jupyter Notebook.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/farinazzarei/adaboost/blob/main/adaboost-from-scratch.ipynb)

Install Jupyter Notebook (if you don't have it yet):

```bash
pip install notebook
```
clone this repository :
```bash
git clone https://github.com/farinazzarei/adaboost.git
cd random-forest
```
Launch Jupyter Notebook:
```bash
jupyter notebook
```
open the notebook file in your browser 
