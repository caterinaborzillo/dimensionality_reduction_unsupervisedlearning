# Dimensionality Reduction task - Machine Learning
Machine Learning project on the implementation of a solution for a dimensionality reduction task using an unsupervised learning approach.

Progetto del corso di Machine Learning sull'implementazione di una soluzione di un task sulla riduzione di dimensionalità tramite un approccio non-supervisionato.

## Details
One of the topics that really interested me about Unsupervised Learning technique is Dimensionality Reduction. As the name itself suggests, this type of problem deals with
high-dimensional data, in particular with the number of input variables in a dataset. Usually, having a large number of features for input data is not bad since the fact that a lot of features give to the model a lot of information about the data, reason why the model should learn and predict more. But it is not always true; first, because if the
number of features is high it may increase the variance of data e then the model could suffer from overfitting. Also, with a lot of variables, the characteristics of the input of
data become very similar and so less meaningful from the point of view of classification. In the end, the point is that too many features are not useful, and that’s why
dimensionality reduction technique is used.

- homework_ML.ipynb: .ipynb file containing the code solution to the dimensionality reduction task
- dimensionality_reduction_task.pdf: .pdf file with the detailed description of the implemented solution; in the report is specified which datasets have been used for training and testing, how data have been preprocessed, which method/algorithm I used, which configurations of the method I have tried, there is a description of the evaluation method used, and the results I obtained using appropriate metrics. The report compares two different solutions. Conclusions discusses the comparative results. Computational training time is also reported and commented.

## Solution Methods: 
1. Principal Component Analysis (PCA)
2. Autoencoders

## Languages, libraries and frameworks
Python, TensorFlow, Keras on Google Colab
