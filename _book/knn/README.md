# KNN

#### Regression KNN

Assign value of unknown point based on average values of closest K neighbours in featurespace

It is important to choose the correct K. Too small, overfit. Too big, smooth too much. 

Using **corss validation** to measure performance. 

**Improving KNN**

距离越远，相似度越小，影响越小

Inverse weighting
$$
weight = k_1/(distance + k_2)
$$
subtraction weighting
$$
weight = max(0,k_1-distance)
$$
Gaussian weighting
$$
weight = exp(-distance^2/k_1^2)
$$
Advantanges:

Disadvantages:

1. computationally expensive (many examples generally means better accuracy)

#### K-D Trees