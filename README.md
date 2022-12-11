# 2021-2-CISC7202-TOOLS-FOR-MACHINE-LEARNING
A hands-on machine learning course: Master the basic methods and tools of common machine learning algorithms.
## Chapter 1: Regression
> - Regression
> - Ridge and Lasso Regression
> - Nearest Neighbor and Kernel Regression

**Assignment 1: Regression**

For this assignment, you have four tasks on the dataset diabetes. The dataset is splitted into training and test data with fix seed (random_state fixed) to ensure the reproducibility.
- Task 1: Fit a linear regression model on training data and evaluate mean_squared_error on testing data
- Task 2: Feature selection using Lasso regression on training data and report the top 4 most informative features
- Task 3: Fit a kernel regression model with the top 4 features and report the mean_squared_error on testing data
- Task 4: Get better performance (lower mean_squared_error on testing data using a model trained on the training data) with any models/hyperparamters/options (mentioned in the lecture or beyond the lecture. The smaller test error you have, the more points you will receive (like a data science competition). Enjoy!
## Chapter 2: Classification
> - Logistic Regression
> - Decision Trees
> - Boosting and Bagging
> - SVM and Naïve Bayes
> - Practical Issues for Classification

**Assignment 2: Classification**

For this assignment, you have three tasks on the dataset penguins (with missing data). 
- Task 1: Feature engineering (20%)
- Task 2: Implement and try different classification techniques (40%)
- Task 3: Hyperparameter tuning via cross validation, using Randomized Search when applicable (40%)
## Chapter 3: Clustering
> - Clustering (K-means, Hierarchical Clustering and Dbscan)
> - Mixture Models
> - Dimensionality Reduction

**Assignment 3: Clustering and Dimensionality Reduction**

For this assignment, you have three tasks on the dataset wine.
- Task 1: Implement and try different clustering techniques (30%)
- Task 2: Evaluate the clustering results against ground truth (30%)
- Task 3: Dimensionality reduction and visualization (40%)
## Chapter 4: Deep Learning
> - Convolutional Neural Networks
> - Generative Neural Networks

**Assignment 4: Deep Learning** 

In this assignment, you are required to implement a deep learning pipeline on CIFAR dataset. The CIFAR-10 dataset (Canadian Institute For Advanced Research) is a collection of images that are commonly used to train machine learning and computer vision algorithms. The CIFAR-10 dataset contains 60,000 32x32 color images in 10 different classes (50000/10000 for training/test)
Your grade will be given according to how far you can achieve the following requirements:
- Task 1: Implement a running CNN pipeline. Your NN consists of at least one CNN layer and one linear layer. (50%)
    - Hint: CIFAR contains RGB-color images, which have three channels. 
- Task 2: Within 20 epochs, your CNN model achieves at least 60% accuracy on testing dataset. (30%)
    - Hint: if you feel the training time is long, think about using Google Colab
- Task 3: Within 20 epochs, the higher accuracy you have, the more points you will receive (like a data science competition). Enjoy! (20%)
