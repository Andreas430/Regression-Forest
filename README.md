# Regression-Forest
*Regression Forest applied to toy problem for visualization*


<p align="justify">A regression forest uses multiple decision trees the output. This is otherwise known as an ensemble learning method, where an algorithm uses multiple other algorithms to obtain a result with higher precision. Bootstrapping occurs on the data for each tree. Bootstrapping uses random sampling with replacement. This helps to decrease the bias. For regression, inventors recommend p/3 number of random features when building each tree. This is a widely known technique called random subspace. Each tree is made up of many branches, also known as splits. The number of splits is called the depth of the tree. Usually, a preset value is used to avoid overfitting and limit it from growing with unlimited depth. Decision trees have two kind of nodes, internal which contain a split and leaf which contain an answer. Avoiding overfitting can also be achieved by setting a prefix minimum for the leaf size number.

The split of each branch can be determined using various techniques. The most popular techniques for regression trees are to minimize variance reduction or to maximize the information gain based on entropy. Both use the variance to the right and to left of the node. This measures how consistent a node is. For this example variance reduction is used.</p>
