# Implementation of fundamental machine learning algorithms from scratch in Python

## About this Repo
This repository contains Python implementations of several fundamental machine learning algorithms built from scratch. The purpose of this repository is to provide a resource for those who want to understand how machine learning algorithms work under the hood. 
Each algorithm is contained within its own directory, and includes one or more Jupyter notebooks with examples of how to use the algorithm. 


## Preparing the environment
**Note**: I have tested the codes on __Linux__. It can surely be run on Windows and Mac with some little changes.

1. Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/iamirmasoud/ml_from_scratch.git
cd ml_from_scratch
```

2. Create (and activate) a new environment, named `ml_env` with Python 3.7. If prompted to proceed with the install `(Proceed [y]/n)` type y.

	```shell
	conda create -n ml_env python=3.10
	source activate ml_env
	```
	
	At this point your command line should look something like: `(ml_env) <User>:ml_from_scratch <user>$`. The `(ml_env)` indicates that your environment has been activated, and you can proceed with further package installations.

3. Before you can experiment with the code, you'll have to make sure that you have all the libraries and dependencies required to support this project. You can install  dependencies using:
```
pip install -r requirements.txt
```


## Algorithms

The algorithms covered in this repository are:

[Decision Tree](Decision Tree)

[Gradient Descent](Gradient Descent)

[K-means](K-means)

[K-nearest neighbors (KNN)](K-nearest neighbors (KNN))

[Linear Regression](Linear Regression)

[Linear Tree](Linear Tree)

[Logistic Regression](Logistic Regression)

[Naive Bayes](Naive Bayes)

[Principal Component Analysis (PCA)](Principal Component Analysis (PCA))

[Support Vector Machine (SVM)](Support Vector Machines (SVM))

[Word2Vec](Word2Vec)


## Structure of Repo
```
.
├── Decision Tree
│   ├── CheatSheetDT.png
│   ├── DecisionTree.py
│   ├── Decision Tree Split Example.ipynb
│   ├── fish.csv
│   ├── Node.py
│   └── train.py
├── Gradient Descent
│   ├── GD Dummy Example.ipynb
│   ├── Gradient Descent.ipynb
│   └── Untitled.ipynb
├── K-means
│   ├── assets
│   └── Kmeans-Clustering.ipynb
├── KNN
│   ├── KNN.ipynb
│   └── KNN.py
├── Linear Regression
│   └── LinearRegression.py
├── Linear Tree
│   └── Linear Tree.ipynb
├── Logistic Regression
│   ├── Logistic Regression - MInimal.ipynb
│   ├── LogisticRegression.py
│   └── Logistic Regression with Batch Gradient Descent.ipynb
├── Naive Bayes
│   ├── NaiveBayes.py
│   ├── spam.csv
│   └── Spam Filtering.ipynb
├── PCA
│   ├── PCA from Scratch.ipynb
│   └── PCA.py
├── README.md
├── requirements.txt
├── SVM
│   ├── SVM_Kernels.Rmd
│   ├── SVM.py
│   └── train.py
└── Word2Vec
    ├── stopwords.txt
    ├── training_text.txt
    └── Word2Vec.ipynb

```