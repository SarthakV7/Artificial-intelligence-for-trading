# Random Forests (Ensembling)

![](images/32-27.png)

![](images/32-49.png)

![](images/35-52.png)

![](images/38-05.png)

![](images/39-35.png)

## Out-of-Bag Estimation

I can be shown that for bagging (or bootstrapping), each tree will uses around 2/3 of the original observations. Therefore, for each observation, it will not be used to train 1/3 of the trees in the forest. We can use the 1/3 of the tree to predict the observation and aggregate all prediction scores. The out-of-bag error can be calculated by aggregating over the entire data set.

![](36-36.png)
![](37-12.png)
![](37-36.png)
![](37-58.png)
![](38-22.png)