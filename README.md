# Diabetes_decison_tree_pruning-

Here I explore the sklearn in-built dataset, the diabetes dataset (regression problem) using the decision tree algorithim and its tree pruning capabilities.

CONCLUSIONS:

- Without any pruning we had a depth of 19 and the numbe of leaves equal to 346. The r^2 score was equal to 0.06.

- Following Grid Search CV we had a r^2 of 0.26.

- Finally using the cost compexity tree pruning technique we had a r^2 score of 0.43. This happened for a ccp alpha of 85.

- Hence at least this dataset cose complexity pruning is the best technique for pruning the tree.

- I am able to get a maximum r^2 score of 0.43 with the decision tree algorithim. 

- Some other algorithim needs to be applied to this dataset to get a even better r^2.
