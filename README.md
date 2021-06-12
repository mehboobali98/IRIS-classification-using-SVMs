# IRIS Plant classification using Support Vector Machines

## Problem Statement

The popular IRIS dataset is used for training of linear and non-linear SVM models. The hyper-parameters are fine-tuned of the models are fine-tuned using K-Fold Cross Validation and GridSearch to improve model performance.

## Data Set

The dataset is made of examples of irises, each represented with a feature vector of dimension 4.
The examples belong to one of 3 categories (setosa, versicolor, and virginica). The feature vectors
contain the width and length of the sepal and of the petals.

### Data Set Characteristics:

- Number of Instances: 150 (50 in each of three classes)
- Number of Attributes: 4 numeric, predictive attributes and the class
- Attribute Information:
  - sepal length in cm
  - sepal width in cm
  - petal length in cm
  - petal width in cm
  - class:
    - Iris-Setosa
    - Iris-Versicolour
    - Iris-Virginica

## Implementation

- The Scikit-learn implementation of linear and non-linear SVM has been used.
- SVM have hyper-parameters which need to be fined tuned for better model performance. The fine-tuning was done using:
  - K-Fold Cross Validation
  - Grid Search

## Linear SVM

### Decision Boundary

The Fig. below shows the decision boundary obtained using Linear SVM.

<p align="center">
<img src="/Resources/linear-svm-db.PNG">
</p>

### Results

The Fig. below shows the cross-validation accuracy of Linear SVM.

<p align="center">
<img src="/Resources/linear-svm-acc.PNG">
</p>

## Non-Linear SVM

### Decision Boundary

The Fig. below shows the decision boundary obtained using Linear SVM.

<p align="center">
<img src="/Resources/non-linear-svm-db.PNG">
</p>

### Results

Detailed results have been provided in the Report.pdf file.

The Fig. below shows the cross-validation accuracy of Linear SVM.

<p align="center">
<img src="/Resources/non-linear-svm-acc.PNG">
</p>

## Frameworks Used

- Scikit-learn

# Directory Structure

<pre>
📦IRIS-classification-using-SVMs
┣ 📂Documents
┃ ┣ 📜Report.pdf
┃ ┗ 📜Task Description.docx
┣ 📂Resources
┃ ┣ 📜linear-svm-acc.PNG
┃ ┣ 📜linear-svm-db.PNG
┃ ┣ 📜non-linear-svm-acc.PNG
┃ ┗ 📜non-linear-svm-db.PNG
┣ 📜Linear_SVM.ipynb
┣ 📜Non-Linear_SVC.ipynb
┗ 📜README.md
</pre>
