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
 - Regression
   - Linear regression
   - Polynomial regression
   - Support Vector Regression (SVR)
   - Decision tree regression
   - Random forest regression

 - Classification
   - Binary classification
   - Multiclass classification
   - Multilabel classification


2. Unsupervised ML
 - Clustering
   - K-means clustering
   - Hierarchical clustering
   - DBSCAN(Density-Based Spatial Clustering of Appications with Noise)

 - Dimensionality Reduction
   - PCA (Principal Component Analysis)
   - t-SNE (t-distributed Stochastic Neighbor Embedding)

 - Association Rule Mining
   - Apriori algorithm
   - FP-Growth  algorithm

 - Anamoly Detection
   - One-class SVM
   - Isolation forest

3. Semi-supervised learning
 - Self-training 
 - Co-Training
 - Label propagation

4. Reinforcement ML
 - Value based methods 
   - Q-Learning
   - SARSA
 - Policy based methods
   -  REINFORCE
   - Actor-Critic methods
 - Model based reinforcement
 - Deep reinforcement learning
