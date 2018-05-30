# PerceptronClassifier
This project contains the implementation of a perceptron classifier which is basically a neuron that accepts an input and weights example of training with it combined in a linear equation
train()
-- The training loop for the perceptron passes through the training dataseveral times and updates the weight vector for each label based on classification errors.
-- Data structure use dhere would be the weights[label] data structure which has weigh of the action to determine the best one
-- These weights are contained by a feature vector.
-- in each iteration for scores[label] the weight datatructure gets updated.
-- The inputs scores are then multiplied by those weights

classify
-- Classifies each example in data as the label that most closely matches the weight vector for that label.
-- Return a list of classes for the data
