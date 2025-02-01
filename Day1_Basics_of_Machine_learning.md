## Machine learning
- ML is the intersection of 2 disciplines - Data Science & Software Engineering
- Goal : To use data to create a predictive model that can be incorporated into a software application or service (Inferencing).

## Some ML terms
1. **Machine learning model** : is a software application that encapsulates a **function** to calculate an output value based on one or more input values.
2. **Training** : process of defining that function
3. **Training data** : data used to train a ML model(mostly 80% of overall dataset), helps the algorithm learn the underlying patterns and relationships.
4. **Testing** : process of evaluating the performance of a trained ML model using the testing data.
5. **Testing data** : or "validation data" is a subset of overall dataset(mostly 20%) that is held back from the training process to assess how well the trained model generalizes to new, unseen data.
6. **Hyperparameters** : numeric settings set before training a model  to control algorithm behavior, to differentiate them from x(feature) & y(label) parameters.E.g learning rate & no.of hidden layers in a neural network.
7. **Labels** : The "target variable/values" or "outcome" that a ML model is trying to **predict**. Labels're only used in SL.
8. **Features** : The individual measurable properties or characteristics of a phenomenon being observed. Features are used as "input" to a ML model.
9. **Inferencing** : process of using a trained ML model to make predictions or decisions on new, unseen data. It is the stage where model applies the knowledge it gained during training to solve real-world problems.

## Types of Machine Learning
1. Supervised ML
 1.1 Regression
  1.1.1 Linear regression
  1.1.2 Polynomial regression
  1.1.3 Support Vector Regression (SVR)
  1.1.4 Decision tree regression
  1.1.5 Random forest regression

 1.2 Classification
  1.2.1 Binary classification
  1.2.2 Multiclass classification
  1.2.3 Multilabel classification


2. Unsupervised ML
 2.1 Clustering
  2.1.1 K-means clustering
  2.1.2 Hierarchical clustering
  2.1.3 DBSCAN(Density-Based Spatial Clustering of Appications with Noise)

 2.2 Dimensionality Reduction
  2.2.1 PCA (Principal Component Analysis)
  2.2.2 t-SNE (t-distributed Stochastic Neighbor Embedding)

 2.3 Association Rule Mining
  2.3.1 Apriori algorithm
  2.3.2 FP-Growth  algorithm

 2.4 Anamoly Detection
  2.4.1 One-class SVM
  2.4.1 Isolation forest

3. Semi-supervised learning
 3.1 Self-training 
 3.2 Co-Training
 3.3 Label propagation

4. Reinforcement ML
 4.1 Value based methods 
  4.1.1 Q-Learning
  4.1.2 SARSA
 4.2 Policy based methods
  4.2.1 REINFORCE
  4.2.2 Actor-Critic methods
 4.3 Model based reinforcement
 4.4 Deep reinforcement learning
