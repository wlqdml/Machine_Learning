# Perceptron-based Classifier for Sentiment Analysis (Amazon reviews)
- **Introduction**:
  - The training/testing datasets contains reviews written by Amazon customers for various food products. The reviews have been adjusted to a +1 or -1 scale, representing a positive or negative review, respectively.
  - The goal is to design a classifier for sentiment analysis.
- **Notebook**: [**Build several linear classifiers based on three algorithms**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/Amazon_Reviews/amazon_linear_classifiers.ipynb)
  - Perceptron, Average Perceptron, Pegasos.

# Single Layer Perceptron and Multilayer Perceptron for a Binary Classification (Toy Data)
- **Introduction**:
  - The goal is to design a binary classifier using a generated toy dataset (classifying two-dimensional points into one of two classes).
  - Using a preceptron-based algorithm to discriminate the points of one class from the other.
  - Compared the performance of perceptrons with different numbers of hidden layers (other hyperparameters, such as learning rate, size of hidden layers are specified, rather than tuned), in scenarios involving linearly separable and not linearly separable toy data.
- **Notebook**: [**Perceptron and Multiple Layer Perceptron Models using PyTorch**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/Perceptron_ToyData/perceptron_mlp_main.ipynb)
  - Model: Perceptron and Multilayer Perceptron
  - Visualization of the training - changes in the loss and the hyperplain (an [application](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/Perceptron_ToyData/perceptron_visualization.ipynb) of Axes.contour)


# Perceptron Classifier for Sentiment Analysis (Yelp Reviews)
- **Introduction**:
  - The goal is to to classify whether restaurant reviews on Yelp are positive or negative using a perceptron.
  - Described the data structures (in a NLP context) and training routine for a supervised training.
  - The Yelp dataset includes 56,000 reviews. This is a sample of the dataset created by Zhang, Zhao, and Lecun (2015).
- **Notebook**: [**Perceptron classifier for sentimental analysis using Yelp reviews data**](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/Yelp_Reviews/yelp_perceptron.ipynb)
  - Model: Perceptron
  - NLP data treatment: Create a mapping (vocabulary) between the tokens and integers; transform a string representation a review to a vectorized representation of the review (one-hot encoding with an "unknown" token and restrictions to infrequent tokens). 
  - Training routine: Group the vectorized data points into batches; define a batch generator function; define classifier, optimizer, and loss function; track the training state (update best model and early stopping status); training iterations (updates the model parameters so that it improves); validation iterations (evaluates model performance); early-stop the training loop if criterion are met.


# Modeling Components
- Training routine: [Link](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/Yelp_Reviews/yelp_perceptron.ipynb)
- Algorithms: [Perceptron](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/Perceptron_ToyData/perceptron_classifiers.ipynb)
- Loss Function
- Visualization: [Perceptron](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/Perceptron_ToyData/perceptron_visualization.ipynb)
- Feature engineering: [One-hot encoding](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/Yelp_Reviews/class_Vectorizer.ipynb) [TFIDF](https://github.com/houzhj/Machine_Learning/blob/main/ipynb/IMDB_Reviews/tfidf.ipynb)

