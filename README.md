# Case study: Handmade KNN on Iris dataset

This case study deals with one specific approach to classification.
The goal is to set up a classifier such that when
it's presented with a new observation whose category is not known,
it will attempt to assign that observation to a category, or a class,
based on the observations for which it does know the true category.
This specific method is known as the k-Nearest Neighbors classifier,
or kNN for short.

For building our KNN classifier, we need to be
able to compute, what is sometimes called, majority vote.
Note that while this method is commonly called "majority vote," what is actually determined is the plurality vote, because the most common vote does not need to represent a majority of votes. 
It is used the standard naming convention of majority vote here.
As the name K-Nearest neighbors suggests, as part of the method,
we need to find which point are the nearest neighbors of any given point
that we're hoping to classify, there distance between points must be computed.

It was applied both the SciKitLearn and our handmade classifier
to a classic data set created by Ron Fisher in 1933, and finally compare the accuracy of both algorithms.
Iris dataset consists of 150 different iris flowers, 50 from each of three different species.
For each flower, we have the following covariates: sepal length, sepal width,
petal length, and petal width.



