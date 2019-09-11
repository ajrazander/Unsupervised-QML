# Unsupervised-QML
Unsupervised quantum machine learning example on the iris dataset using [qiskit](https://qiskit.org). The dataset can be found on Kaggle: [iris data set](https://www.kaggle.com/uciml/iris#Iris.csv).

First, the classical k-means clustering algorithm is used on the dataset. Results are very accurate. Second, the data points are mapped to a graph where the quantum max-cut problem is solved on a quantum computing using the QAOA. Results are very accurate.