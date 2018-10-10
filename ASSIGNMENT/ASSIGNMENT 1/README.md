PROBLEM 1 :<br>

Using Keras, build a MLP to classify the CIFAR-10 dataset. Note that each record is of size
1*3072. Starting with the MNIST example code, build a MLP to classify the data into the 10
classes.
Modify the following parameters and discuss the effect of changing parameters on loss and
accuracy.
1. No of epochs
2. Batch size
3. Network configuration
a. Number of neurons in a layer
b. Number of layers
4. Learning rate
5. Activation functions
6. Dropout rates
Ensure you are building the model with the training data set and validating against the provided
test data set.
• You are expected to provide a recommendation for the best model you would
recommend for classification. Which model (with parameter values) would you choose
and why?<br>
• Commentonhowgoodyourmodelis?Doesitoverfit/underfitdata?Whatcouldyou
do to improve the model?

PROBLEM 2 :

PART A :<br>
Build model using Functional API 

PART B :<br>
Abstract out constants to a configuration file( You are free to choose the format of the configuration file.It could be
another .py file, csv, json etc.). Please convert the code to a jupyter notebook
Starting from the base case, try different experiments to see if you can get better accuracy. Design your
model such that you can easily change parameters and rerun experiments.
Discuss at-least 3 experiments with different parameters and your best model. Also comment on which
parameters you thought helped better accuracy compared to that of the base case.
