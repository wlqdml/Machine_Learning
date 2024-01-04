# Perceptron-based Linear Classifier for Sentiment Analysis
- Introduction:
  - The training/testing datasets contains reviews written by Amazon customers for various food products. The reviews have been adjusted to a +1 or -1 scale, representing a positive or negative review, respectively.
  - The goal is to design a classifier for sentiment analysis.
- [**Build several linear classifiers based on three algorithms**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/Amazon_Reviews/amazon_linear_classifiers.ipynb)
  - Perceptron, Average Perceptron, Pegasos.
  - Feature engineering / hyperparameter tuning
  - NLP data treatments (stopwords, bag of words) 

# Single Layer Perceptron and Multilayer Perceptron for a Binary Classification (Toy Data)
- Introduction:
  - The goal is to design a binary classifier using a generated toy dataset (classifying two-dimensional points into one of two classes).
  - Using a preceptron-based algorithm to discriminate the points of one class from the other.
  - Compared the performance of perceptrons with different numbers of hidden layers (other hyperparameters, such as learning rate, size of hidden layers are specified, rather than tuned), in scenarios involving linearly separable and not linearly separable toy data.
- [**Perceptron and Multiple Layer Perceptron Models using PyTorch**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/Perceptron_ToyData/perceptron_mlp_main.ipynb)
  - Model: Perceptron and Multilayer Perceptron
  - Loss (Binary Cross-Entropy): nn.CrossEntropyLoss()
  - Optimizer: optim.Adam()
  - Visualization of the training - changes in the loss and the hyperplain (an [application](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/Perceptron_ToyData/perceptron_visualization.ipynb) of Axes.contour)
