# Active-Learning Strategies

## In this project, we will make a comparison between 3 active learning strategies and a random strategy using two datasets :

##  Dataset used :

### (1) Load digits : This classification contains data points, where each data point is an 8X8 image of a single digit.

### (2) iris dataset : The Iris Dataset contains four features (length and width of sepals and petals) of 50 samples of three species of Iris (Iris setosa, Iris virginica, and Iris varicolored). These measures were used to create a linear discriminant model to classify the species.

## Active-Learning


➢ Active learning is a machine learning approach where a model iteratively selects and queries the most informative data samples from a large unlabeled dataset and then incorporates the labeled data to improve its performance

➢ The goal of active learning is to minimize the labeling effort while maximizing the model's learning capacity. By selectively choosing which instances to label


## Applied Strategies  :

### (1) Uncertainty sampling strategy

It is a strategy used in machine learning for selecting the most informative data points to be labeled by an expert or a human annotator.The uncertainty sampling strategy works by first training a model on a subset of labeled data, then using the model to predict the labels of the remaining unlabeled data.The samples with the highest uncertainty score are then selected for labeling

### (2) Margin sampling strategy

The margin sampling strategy works by first training a model on a subset of labeled data, then using the model to predict the labels of the remaining unlabeled data. For each example, the difference between the two highest predicted probabilities is calculated, and the examples with the smallest margin are selected for labeling




### (3) Entropy sampling strategy
 
The entropy sampling strategy works by first training a model on a subset of labeled data, then using the model to predict the labels of the remaining unlabeled data. For each example, the entropy of the predicted probabilities is calculated, and the examples with the highest entropy are selected for labeling.
