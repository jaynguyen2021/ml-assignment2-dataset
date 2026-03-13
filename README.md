# Machine Learning Assignment 2  
## Neural Network Hyperparameter Analysis (Iris Dataset)

### Dataset
The dataset used in this assignment is the Iris dataset.

Dataset link:  
https://raw.githubusercontent.com/jaynguyen2021/ml-assignment2-dataset/refs/heads/main/iris.data

The dataset contains 150 samples with four numerical features:
- sepal length
- sepal width
- petal length
- petal width

The goal is to classify each sample into one of three species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica


### Requirements
The code was tested using Python 3.x with the following libraries:

- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  

You can install them using: 
pip install numpy pandas matplotlib seaborn scikit-learn

---

### How to Run

1. Install the required libraries.

2. Run the Python script:
ML_Assignment_2_NeuralNetwork_Iris.ipynb


The dataset will be loaded directly from the online URL, so no local dataset file is required.

---

### Output

Running the script will generate the following outputs:

- Training history plots showing loss curves for different models
- A table showing hyperparameter experiment results
- Best model configuration and performance metrics
- A confusion matrix for the best model

These outputs help analyze how different neural network hyperparameters affect model performance.

---

### Implementation Notes

The original starter code suggested implementing the neural network using NumPy with manual forward and backward propagation.

In this implementation, **scikit-learn's `MLPClassifier`** was used instead. This library provides a built-in implementation of a multilayer perceptron neural network trained using backpropagation.

The focus of this assignment was on experimenting with different hyperparameters, including:

- activation functions
- learning rates
- number of training iterations
- number of hidden layers

Using `MLPClassifier` allowed the experiments to focus on **hyperparameter tuning and performance analysis** rather than implementing the neural network training algorithm from scratch.
