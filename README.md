# Alphabet Venture Funding
These are a Google CoLab notebook that look at historial data and codes it into a neural network to predict wheather a venture will be successful or not. Some of the inputs for the applications who are looking for funding are Affiliaion, Special Consideration, Income Amount, Asking Amount and if this comapany is successful or not. From these preamiters we train a nureal network model to assign a 1 or 0 thgins that are not intergers. We scale the data to become more accurate and run the networks. The steps for these Google Colab notebooks are are broken out into the following sections: Prepare the data for use on a neural network model. Compile and evaluate a binary classification model using a neural network. Finally we optimize the neural network model. The conclusiton is listed in the main notebook. 

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - An Open Source Machine Learning Framework for Everyone

* [tensorflow](https://www.tensorflow.org/) - The fundamental package for scientific computing with Python

* [keras](https://github.com/keras-team/keras) - Keras is an API designed for human beings, not machines. Keras follows best practices for reducing cognitive load
    Dense, Sequential

* [sklean.metrics](https://github.com/scikit-learn/scikit-learn) - Simple and efficient tools for predictive data analysis  
    OncHotEncoder, StandardScaler, train_test_split

* [GoogleColab](https://colab.research.google.com/) - Colab, or "Colaboratory", allows you to write and execute Python in your browser, with zero configuration required, access to GPUs free of charge, easy sharing

## Installation Guide

Before running the application first install the following dependencies. Note that if you are running on the cloud and not locally you will have to run all lines of code.

```
import pandas as pd
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder

```

---
## Usage

These are located in a Google CO Lab notoebook. You can access googlecolab by going to https://colab.research.google.com/ 

Conclusions are located in the main notebook compairing the three models. The second notebook containes the model that removes some of the inputs that may have confused the neural network.  

---

## Examples
```
# Add the first hidden layer
nn.add(Dense(units = hidden_nodes_layer1, input_dim= number_input_features, activation = 'relu'))
# Add the second hidden layer
nn.add(Dense(units= hidden_nodes_layer2, activation = 'relu'))
# Add the output layer to the model specifying the number of output neurons and activation function
nn.add(Dense(units = number_output_neurons, activation = 'linear'))

```

---

## Contributors

DU Starter Code
Terrence McCoy


---

## License

MIT