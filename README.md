
# Performing Predictive Analysis for Breast Cancer Diagnostics
### With K-Means Clustering and Random Forest Algorithms in Python with JupyterLab

####  Source
This dataset was pulled from Kaggle, and comprises a set of nuclei features for breast tumor diagnosis. 

Source and feature details:
>[UCI ML Breast Cancer Wisconsin Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
>Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
>Attribute Information:
>1) ID number
>2) Diagnosis (M = malignant, B = benign)
>3-32)Ten real-valued features are computed for each cell nucleus:

>a) radius (mean of distances from center to points on the perimeter)

>b) texture (standard deviation of gray-scale values)

>c) perimeter

>d) area

>e) smoothness (local variation in radius lengths)

>f) compactness (perimeter^2 / area - 1.0)

>g) concavity (severity of concave portions of the contour)

>h) concave points (number of concave portions of the contour)

>i) symmetry

>j) fractal dimension ("coastline approximation" - 1)

>The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, >field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

####  Initial Cleaning and Processing Steps

####  Initial Random Forest Analysis

####  Principal Component Analysis

![PCA30](https://github.com/ElishaPhillips/Python-K-Means-RandomForest-Wisconsin-Breast-Cancer-Diagnostics/blob/9c7d169e99817ed944578b93f33bdc127881913a/Graphs/Visualising30.png)

![PCA10](https://github.com/ElishaPhillips/Python-K-Means-RandomForest-Wisconsin-Breast-Cancer-Diagnostics/blob/9c7d169e99817ed944578b93f33bdc127881913a/Graphs/Visualising10.png)

####  K-Means Clustering

![KMeansAnalysis](https://github.com/ElishaPhillips/Python-K-Means-RandomForest-Wisconsin-Breast-Cancer-Diagnostics/blob/9c7d169e99817ed944578b93f33bdc127881913a/Graphs/BCWD.KCluster.png)

####  Random Forest with 10 Principal Components

![RandForestAnalysis](https://github.com/ElishaPhillips/Python-K-Means-RandomForest-Wisconsin-Breast-Cancer-Diagnostics/blob/9c7d169e99817ed944578b93f33bdc127881913a/Graphs/BCWD.RandTree.png)

####  Results







