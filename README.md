# Credit Card Fraud Detection using Gradient Boosting
- Introduction:
  - This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.
  - The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
  - It contains only numerical input variables which are the result of a [PCA transformation](https://en.wikipedia.org/wiki/Principal_component_analysis).
  - Feature 'Class' is the target feature variable and it takes value 1 in case of fraud and 0 otherwise.
- Data [[Link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)]
- [**Exploratory data analysis and oversampling**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/credit_card_fraud_EAD_oversampling.ipynb)
- [**Hyperparameter Tuning**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/credit_card_fraud_hyperparameter.ipynb)

# Sentimential Analysis using IMDB Reviews (TFIDF + Gradient Boosting)
- Introduction:
  - IMDB dataset having 50,000 movie reviews for natural language processing or Text analytics.
  - The goal is to predict the "sentiment" class which takes value "positive" or "negative".
- Data [[Link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)]
- [**Data treatment and feature engineering**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/imdb_data.ipynb)
  - [**More about creating features using TFIDF**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/tfidf.ipynb)
- [**Feature selection (Iterative Reduction, Boruta)**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/imdb_feature_selection.ipynb)
  - [**Random noise feature test**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/imdb_random_noise_test.ipynb): evaluate feature selection methods, according to whether they are able to identify random noise feautures.
  - [**Boruta analysis**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/imdb_boruta_analysis.ipynb): Conducting Burota feature selection using different combinations of algorithms (LGB,XGB, Random forest) and type of feature importance (gain,split,cover,weight,impurity)

# A Linear Classifier for Sentiment Analysis
- Introduction:
  - The training/testing datasets contains reviews written by Amazon customers for various food products. The reviews have been adjusted to a +1 or -1 scale, representing a positive or negative review, respectively.
  - The goal is to design a classifier for sentiment analysis.
- [**Build several linear classifiers based on three algorithms**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/topic_linear_classifiers.ipynb)
  - Perceptron, Average Perceptron, Pegasos.
  - Hyperparameter tuning
  - Feature engineering
  - Overfitting
  - NLP data treatments (stopwords, bag of words) 

# SVM and Multinomial (Softmax) Regression Models for MNIST Handwritten Digit Classification
- Introduction:
  -  The [MNIST](https://academictorrents.com/details/323a0048d87ca79b68f12a6350a57776b6a3b7fb) (Mixed National Institute of Standards and Technology) database contains 60,000 training digits and 10,000 testing digits, all of which have been size-normalized and centered in a fixed-size image of 28 × 28 pixels.
  -  The goal is to predict the label (0-9) of the digit.
 - [**Build classification models based on SVM(Support Vector Machine) and  Multinomial (Softmax) Regression**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/mnist_SVM.ipynb)
  - Linear SVM
  - Polynomial SVM 
  - Radial basis function SVM
  - Multinomial (Softmax) Regression

# A Supervised Training Loop for a Perceptron and Binary Classification (Toy Data)
- Introduction:
  - The goal is to design a binary classifier using a generated toy dataset (classifying two-dimensional points into one of two classes).
  - Using a Preceptron algorithm, i.e, learning a single line (decision boundary or hyperplane) to discriminate the points of one class from the other. 
  - Illustrates the steps of a classic supervise learning: constructing data, specifying a model and a loss function, setting up an optimization algorithm, updating model parameters with gradients, generating predictions. 
- [**Supervised Training Loop using PyTorch**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/topic_perceptron_loop.ipynb)
  - Model: nn.Linear()
  - Loss (Binary Cross-Entropy): nn.BCELoss()
  - Optimizer: optim.Adam()
  - Visualization of the training - changes in the loss and the hyperplain (an [application](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/topic_contour.ipynb) of Axes.contour)


