# nonsymmetricalFish
Unsupervised/Clustering Machine Learning

## Project Overview:

* The goal is to cluster fish.
* There are 4 different fish species. Find how well they cluster
together.
* Also, suppose we don't know the fish species. Determine the optimal
number of clusters.
* Find the correlation amongst the different features
* Use Dimension Reduction to reduce the number of features

## Code and Resources Used

### python version: 3.6
### Packages: pandas, numpy, sklean, matplotlib, seaborn

## Data
These fish measurement data were sourced from the Journal of
Statistics Education. (fish.csv)

* Species
* Weight
* Length1
* Length2
* Length3
* Height
* Width

## Model Building

* Build a pipeline with standard scaler and kmeans model
* Fit and predict the labels on the fish. Compare to original label.
* How many clusters: Plot the model inertia with various clusters to
determine the optimal number of clusters. Notice that inertia slowly
decreases between 4 and 5 clusters.
* Find correlation between 6 different features.
* Use PCA to reduce number of features to 2
* Use PCA features to plot different fish species.

