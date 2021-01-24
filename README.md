# TensorFlow-TitanicDataset
A Jupyter Notebook that uses a TensorFlow LinearClassifier model on the Titanic Passenger Dataset from Google. The dataset includes 
information about the passengers' gender, class, age, and whether they survived amongst other data. Given a set of training data and a set of testing data, the goal is to derive feature columns from the given information and train our model to order to predict whether the passengers in the test data set survived. 

## Project Status
This project is based off a TensorFlow tutorial, but expands on that tutorial by creating crossed feature columns and tuning the epoch parameter, in order to find the number of epochs that maximizes the accuracy of our model. I plan to add a Keras Optimizer in the LinearClassifier in order to configure the learning rate, and find the rate that mizimized the accuracy of the model, like I have done for the number of epochs. 

## Requirements 
- Python3 
- TensorFlow (Version 2.4.0 on my machine) 
- numpy (Version 1.19.4 on my machine)
- matplotlib (Version 3.3.3 on my machine)
- IPython (Version 7.19.0 on my machine) 

## References 
https://www.tensorflow.org/tutorials/estimator/linear

https://www.tensorflow.org/api_docs/python/tf/compat/v1/estimator/LinearClassifier

https://www.youtube.com/watch?v=tPYj3fFJGjk&t=16858s
