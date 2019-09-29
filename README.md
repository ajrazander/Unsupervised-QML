# Unsupervised-QML
Unsupervised quantum machine learning example on the iris dataset using [qiskit](https://qiskit.org). The dataset can be found on Kaggle: [iris data set](https://www.kaggle.com/uciml/iris#Iris.csv).

The [first notebook](https://github.com/ajrazander/Unsupervised-QML/blob/master/Max-cut.ipynb) is a comparison between a classical and a quantum unsupervised learning algorithm. First, the classical k-means clustering algorithm is used on the dataset. Results are very accurate. Second, the data points are mapped to a graph where the quantum max-cut problem is solved on a quantum computing using QAOA. Results are very accurate.

The [second notebook](https://github.com/ajrazander/Unsupervised-QML/blob/master/Max-cut%202%2B%20Divisive%20Clustering.ipynb) is a divisive hierarchical scheme allowing the max-cut problem solved by QAOA to cluster data into 2+ groups. Results are very accurate.