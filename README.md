# Live Classification using TensorFlow.JS on Iris dataset
A tensorflow.js web application to perform classification and prediction on the Iris dataset using TensorFlow Keras API.

## Dataset

The dataset used is Iris and the two linearly separable species (Virginica and Versicolor) are combined together to convert it into a binary classification problem. The original iris dataset looks like this:

<br>
<center> <img src = "imgs/iris_orig.png"> </center>
<br>

As we can see the two classes 1 and 2 are linearly inseparable and we combine them together for this tutorial. After we combine the classes the new graph would look like this:

<br>
<center> <img src = "imgs/iris_modified.png"> </center>
<br>

Also, note that only 2 (sepal width, petal width) out of the 4 (sepal width, petal width, sepal length, petal length) features have been selected for classification.

## Classification Model in tf.js
Classification is performed using this dataset in tensorflow.js and the application takes user input in the form of `Sepal Width` and `Petal Width` through the browser and the model classifies the example into one of the two categories creates above and displays them in different colors.

## Live Demo
