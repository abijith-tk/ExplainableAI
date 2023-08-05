## Decision Tree Classifier

Supervised Learning algorithm that can be used for both classification and regression problems. 

It is a tree structured classifier, where the internal nodes represent the features of the dataset, branches represent the decision rule and leaf nodes represents the outcome.

Two types of nodes 

- Decision Node : Used to make any decision and have mulitiple branches 
- Leaf Node : Represents the outcome

#### How to select the best attribute?

##### Information Gain 

Information gain is used to decide which feature to split on each step in building the tree. It measures how much infirmation a feature gives us about the class. The split with higest inormation gain will be taken as the first split and the process continues until all children nodes are pure or the information gain is 0.


#### Advantages  

- Simple to understand 
- Can handle both numerical and categorical data

#### Disavantages

- Prone to overfitting 
- For more class labels, the computational complexity of the decison tree may increase  
- Need to be careful wit hparameter tuning 