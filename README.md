# EasyCaptcha solver

A [EasyCaptcha](https://github.com/pig-mesh/easy-captcha) solver based on PCA and SVM
<img src="./demo.png"/>

## Usage

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1d9ZBo6VvrCgEgwkGlBQWTeUsutHb8dHJ?usp=sharing)

### Running locally

1. Clone this Repository
2. Install requirements
3. Unzip captcha.zip
4. Open captcha_clf.ipynb in Jupyter Notebook

## Datasets

### Training set

* 50 Labeled Captcha
* 450 Unlabeled Captcha

### Test set

* 1000 Labeled Captcha

## Result
* Captcha Accuracy: 98.9%
* Characters Overall Acc: 99.72%
* Characters Average Acc: 99.64%
### Confusion Matrix
<img src="Confusion_Matrix.png">

### Visualization of features
<img src="Visualization_of_features.png">