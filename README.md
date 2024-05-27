# NTU-BMDSIS
### We have done many classifications toward the DNA-protein binding modeling. And the result shows satisfying in the classification of 80% of samples are assigned to be training dataset and rest will be testing dataset, as the number of positive data and negative data are same in both training and testing dataset (Classification 2).

### However, once we have each protein divided into 80% training and 20% testing (Classification 3) or make there is no common protein in training set and testing set (Classification 4), the performance of the modeling will reduce and would not reach our expectation. But there are some models perform well in some aspects (precision and MCC) of the classification.

### Besides, the models with decision trees as basic structural showed better performance than other models, so that we need to do more analyzation toward this in the future.

### In conclusion, if we have a huge dataset that including all the DNA sequences and correlated protein sequences, we can train a model that have satisfying performance. However, such huge dataset requires really a lot of sources. Therefore, the features of One-hot encoding, Word2Vec encoding and ESM encoding are not enough for modeling, as we should discover some new features to show the deep-dive relationships of the DNA and protein.
