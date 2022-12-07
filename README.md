# Machine-Learning-Room-Occupancy
An intelligent system based on neural networks to detect the occupancy of an office room from sensors data. Including implementation,  testing,  exploration of behaviour and explanation of the system, also optimisation. 

Using this dataset: https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+

Task was to create an intelligent system based on neural networks to detect the occupancy of an office room from sensors data. Including implementation,  testing,  exploration of behaviour and explanation of the system, also optimisation. 

It was required to perform experimental tests varying the number of free parameters of the model, running several experiments. Elements included; exploring the behaviour of the model during training, under different conditions, and calculating basic statistics to summarise performance in training and testing 

The solution consists of a neural network, built and optimised by experimenting with tuning hyper-parameters to incrementally improve performance on the training set and a held out validation set. Python programming language is used with various applicable libraries. A grid search is used to identify the best parameters from a selection at each step, evaluating performance using a combination of a validation set and k-fold cross validation. 

## Cross validation results of tuning to find the best structure of the neural network:
![image](https://user-images.githubusercontent.com/74421484/206244553-6944b900-abe3-4c84-bd90-ee5a8be48090.png)

## Cross validation results of tuning other hyper-parameters:
![image](https://user-images.githubusercontent.com/74421484/206244645-079c8b84-e82a-419d-8ae6-7048cb1bdb4a.png)

## Model Details:
![image](https://user-images.githubusercontent.com/74421484/206244735-75f9ca8a-2664-4108-ad43-94f78a51b876.png)



