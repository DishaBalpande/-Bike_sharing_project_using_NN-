# Bike_Sharing_Project_Using_NN

 Neural Network developed during my Deep Learning Fundamentals Nanodegree at Udacity. In this project, I created a simple neural network to use it to predict daily bike rental ridership.
 
 I’ve built my own neural network from scratch in my_answers.py file (later on, the file content is imported to my notebook).

Firstly, I created Neural Network class with the init function acommodating the number of input, hidden and output nodes. Next, I initialized the weights, defined the activation function and learning rate.

The values for hidden, output nodes, number of iterations and the learning rate are being set later and can be modified until we get the desired accuracy.

Then, I defined the train function that includes the feed-forward pass, backpropagation, the weights update after each iteration and a run function. All these functions are defined after the train function. In the notebook I started by cleaning and organizing the data, then splitting them into training, test and validation datasets. Next, NN class instance is being created with the input values and hyperparameters passed as arguments.
 
# Prerequisites
 1. Python 3.7
 2. Numpy (win-64 v1.15.4)
 3. Pandas (win-64 v0.23.4)
 4. Matplotlib (win-64 v3.0.2)
 5. Jupyter Notebook
 
# Getting Started

  This Bike-Sharing-Dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number of riders is split between casual and registered, summed up in the cnt column. 
  Below is a plot showing the number of bike riders over the first 10 days or so in the data set. (Some days don't have exactly 24 entries in the data set, so it's not exactly 10 days.) You can see the hourly rentals here. This data is pretty complicated! The weekends have lower over all ridership and there are spikes when people are biking to and from work during the week. Looking at the data above, we also have information about temperature, humidity, and windspeed, all of these likely affecting the number of riders. You'll be trying to capture all this with your model.
  
  
![dataset](https://user-images.githubusercontent.com/55234691/89716685-b915f080-d9cc-11ea-81d7-9a9fe025e753.png)
