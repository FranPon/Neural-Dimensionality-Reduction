# Neural-Dimensionality-Reduction
📊 In this notebook, we will analyze how dimensionality reduction can be performed using a neural network. Dimensionality reduction is a crucial aspect of data analysis as it simplifies complex datasets, reduces noise, improves data visualization, and decreases computation times for machine learning models.

In particular, we will explore different types of neural networks, highlighting the main differences compared to traditional methods such as t-SNE and PCA. PCA, or Principal Component Analysis, is based on a linear decomposition of variances, which transforms the original data into a new coordinate system where the maximum variance of the data is captured along the first axes, thus allowing for effective dimensionality reduction. In contrast, t-SNE is a non-linear visualization technique that preserves local distances between data points, making it useful for visualizing complex structures in high-dimensional data.

Additionally, we will explore the embedding learned by the network both in terms of graphical representation (i.e., in terms of 2D representation) and in terms of reconstructing the original data from its compressed form. This will allow us to evaluate the effectiveness of the neural network in maintaining the salient features of the original dataset and providing an intuitive and informative visualization of the data in a reduced space.

🚀 Following the principle "start small, then scale up," all experiments will be conducted using the MNIST dataset.
