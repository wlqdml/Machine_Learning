# Perceptron-based Linear Classifier for Sentiment Analysis
- Introduction:
  - The training/testing datasets contains reviews written by Amazon customers for various food products. The reviews have been adjusted to a +1 or -1 scale, representing a positive or negative review, respectively.
  - The goal is to design a classifier for sentiment analysis.
- [**Build several linear classifiers based on three algorithms**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/topic_linear_classifiers.ipynb)
  - Perceptron, Average Perceptron, Pegasos.
  - Hyperparameter tuning
  - Feature engineering
  - Overfitting
  - NLP data treatments (stopwords, bag of words) 



# A Supervised Training Loop for a Perceptron and Binary Classification (Toy Data)
- Introduction:
  - The goal is to design a binary classifier using a generated toy dataset (classifying two-dimensional points into one of two classes).
  - Using a Preceptron algorithm, i.e, learning a single line (decision boundary or hyperplane) to discriminate the points of one class from the other. 
  - Illustrates the steps of a classic supervise learning: constructing data, specifying a model and a loss function, setting up an optimization algorithm, updating model parameters with gradients, generating predictions.
  - The codes are mostly based on PyTorch, Numpy and Matplotlib.
- [**Supervised Training Loop using PyTorch**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/topic_perceptron_loop.ipynb)
  - Model: nn.Linear()
  - Loss (Binary Cross-Entropy): nn.BCELoss()
  - Optimizer: optim.Adam()
  - Visualization of the training - changes in the loss and the hyperplain (an [application](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/topic_contour.ipynb) of Axes.contour)
