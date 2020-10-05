![](./assets/heart.png)
<h1 align='center'>Heart Disease Prediction using Machine Learning</h1>
<p align="center">
  <a href="https://github.com/SandeepBalachandran/Heart-Disease-Classifier/releases/" target="_blank">
    <img alt="GitHub release" src="https://img.shields.io/github/v/release/SandeepBalachandran/Heart-Disease-Classifier?include_prereleases&style=flat-square">
  </a>

  <a href="https://github.com/SandeepBalachandran/Heart-Disease-Classifier/commits/master" target="_blank">
    <img src="https://img.shields.io/github/last-commit/SandeepBalachandran/Heart-Disease-Classifier?style=flat-square" alt="GitHub last commit">
  </a>

  <a href="https://github.com/SandeepBalachandran/Heart-Disease-Classifier/issues" target="_blank">
    <img src="https://img.shields.io/github/issues/SandeepBalachandran/Heart-Disease-Classifier?style=flat-square&color=red" alt="GitHub issues">
  </a>

  <a href="https://github.com/SandeepBalachandran/Heart-Disease-Classifier/pulls" target="_blank">
    <img src="https://img.shields.io/github/issues-pr/SandeepBalachandran/Heart-Disease-Classifier?style=flat-square&color=blue" alt="GitHub pull requests">
  </a>

  </br>

  <a href="https://standardjs.com" target="_blank">
    <img alt="ESLint" src="https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat-square">
  </a>
  
  <a href="" target="_blank">
    <img alt="ESLint" src="https://img.shields.io/github/stars/SandeepBalachandran/Heart-Disease-Classifier">
  </a>
  
  <a href="" target="_blank">
    <img alt="ESLint" src="https://img.shields.io/github/forks/SandeepBalachandran/Heart-Disease-Classifier">
  </a>
  
</p>
<hr>

A machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.

* Problem definition
* Data
* Evaluation
* Features
* Modelling
* Experimentation

## 1. Problem Definition

In a statement,

Given cliical parameters of a patient, can we predict whether or not they have heart disease?

## 2. Data

Data obtained from the Cleavland data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/Heart+Disease
## 3. Evaluation

If we can reach 95% accuracy in predicting whether or not a patient has heart disease during the proof of concept, we will pursue the project

## 4. Features

Create data dictionary

* age- age in years
* sex- (1 = male; 0 = female)
* cp- chest pain type
* trestbps- resting blood pressure (in mm Hg on admission to the hospital)
* chol- serum cholestoral in mg/dl
* fbs- (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* restecg- resting electrocardiographic results
* thalach- maximum heart rate achieved
* exang- exercise induced angina (1 = yes; 0 = no)
* oldpeak- ST depression induced by exercise relative to rest
* slope- the slope of the peak exercise ST segment
* ca- number of major vessels (0-3) colored by flourosopy
* thal- 3 = normal; 6 = fixed defect; 7 = reversable defect
* target- 1 or 0

### Preparing the tools

The following tools are going to be used for data analysis, manipulation and modelling:

* [Pandas](https://pandas.pydata.org/docs/).
* [Matplotlib](https://matplotlib.org/contents.html)
* [Numpy](https://matplotlib.org/contents.html)
* [Scikit Learn](https://scikit-learn.org/stable/user_guide.html)

## 5. Results

### Feature importance

![Feature Importance](https://github.com/sandeepbalachandran/Heart-Disease-Classifier/blob/master/plots/feature_importance.png)

### Correlation matrix

![Correlation Matrix](https://github.com/SandeepBalachandran/Heart-Disease-Classifier/blob/master/plots/correlation_digram.png)

### ROC curve

![ROC Curve](https://github.com/sandeepbalachandran/Heart-Disease-Classifier/blob/master/plots/roc_curve.png)

Please Add your suggestions to improve the model. Every thoughts are welcome.
