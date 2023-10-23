# Carcinoma Classifier
The logistic regression algorithm trained on the TCGA transcriptomics dataset of rna-seq to classify three different human cancers.

## Introduction

This repository contains a carcinoma classifier that was trained on an RNA-Seq cancer dataset extracted from the TCGA database. The dataset consisted of 1845 cancer samples measured across 16340 genes, and a label file containing the labels or subtypes of the 1845 samples as either breast invasive carcinoma, kidney clear cell carcinoma, or lung adenocarcinoma.

The classifier was trained using the following algorithms:

* Logistic regression
* Support vector machine (SVM)
* K-nearest neighbors (KNN)
* Random forest
* Gaussian naive Bayes (GNB)

The logistic regression algorithm achieved the highest accuracy score on the dataset, with an accuracy of 99.67%. The classifier was then trained on all three classes, and achieved the following evaluation metrics:

```
                                precision    recall  f1-score   support

  breast invasive carcinoma       1.00      1.00      1.00       321
kidney clear cell carcinoma       0.99      0.99      0.99       133
        lung adenocarcinoma       1.00      0.99      1.00       155
```


## Installation

To run the Jupyter Notebook file in this repository, you will need to have the following software installed:

* Python 3
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-Learn

You can install these dependencies using the following command:

`pip install jupyter numpy pandas scikit-learn`

Once the dependencies are installed, you can clone the repository using the following command:

`git clone https://github.com/aysanraza/carcinoma-classifier.git`

## Usage

Once the dependencies are installed, you can run the Jupyter Notebook file by typing the following command in a terminal:

`jupyter notebook carcinoma_classifier.ipynb`

## Version History
* 0.1
  * Initial Release

## License
This project is licensed under the  MIT license - see the LICENSE.md file for details

## Authors
* Ahsan Raza
  * aysanraza@gmail.com
  * [Linkedin](https://www.linkedin.com/in/ahsan-raza-0510b1128/)
