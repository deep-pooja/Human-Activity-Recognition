## Smart Phone Based Human Activity Recognition
In this project,I explored this [dataset](http://archive.ics.uci.edu/ml/datasets/Smartphone-Based+Recognition+of+Human+Activities+and+Postural+Transitions). This is basically a
classification problem. I have tried various classical machine learning models like SVM, K-NN, Desicion tree and logistic regression to get state-of-the-art accuracy.Finally I have also used deep learning models like multilayer perceptron and 1D conv-net. Uniqueness of the datset set is that it has 512 features that is the feature space has 512 dimensions.

Result of the predictive models:

| Model        | Accuracy       
| ------------- |:-------------:|
|logistic regression|Test Accuracy: 0.9500316255534472|
| MLP     | Test accuracy: 0.932 |
| 1D Conv | Test accuracy: 0.917|
| SVM ker = rbf | Test accuracy: 0.941808981657179| 
|SVM ker = linear | Test accuracy: 0.9487666034155597|
|SVM ker = Polynomial|Test accuracy: 0.92662871600253|
|KNN |Test set Accuracy:  0.8548387096774194|
|Decision Tree| DecisionTrees's  Test Accuracy:  0.8358633776091081 |

# deep-learning model
![i](mlp.png)

# classical machine-leaning models
![1](knn.png)

![2](dt.png)
