# PCA for Dimension-Reduction
Ameena Gaji (Craft and Hawkins Department of Petroleum Engineering), agaji1@lsu.edu

One of the most important applications of Principal Component Analysis (PCA) is for dimensionality reduction. 

# Data Loading and Preparation
- Loads the Iris dataset consisting of data of 3 species (setosa, virginica and versiolor), a classic open-source dataset, commonly used for testing classification and clustering methods.
- Extracts the feature matrix X (sepal length, sepal width, petal length, petal width) and the target vector y (species).
- Standardizes the feature matrix by subtracting the mean and scaling (dividing by the standard deviation) to have zero mean and unit variance, which is a common requirement for optimal performance.

# Steps: PCA

- Constructs the covariance matrix for the standardized feature matrix, capturing how each variable varies with the others.
- Computes the eigenvectors and eigenvalues of the covariance matrix, which are critical for understanding data variability and determining the principal components.
- Sorts the eigenvalues and the corresponding eigenvectors in descending order to rank the principal components in terms of how much variance they capture from the dataset.
- Transforms the 4D data into 2D by projecting it onto the two most significant principal components, effectively reducing the dataset's dimensionality while retaining most of the original variability.

# Data Visualization:

- Plots the 2D representation of the dataset obtained through PCA, using different colors for different species.
- Displays the plot with axes (PC_1 and PC_2) as the 2 principal components.


![download (2)](https://github.com/Meegaj/Dimension-Reduction/assets/125159642/c7ee8e34-8dfc-48f1-9b07-ab896b205ed6)

# References
Iris dataset: wikipedia.org/wiki/Iris_flower_data_set
