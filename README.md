# Handwritten-Digit-Predictor

I used Logistic Regression to guess handwritten numbers (0 to 9) using Python.

The dataset I used was already available in sklearn, it has images of digits in pixel form.

First, I showed some digit images using matplotlib just to see how they look.

Then I split the data into training and testing using train_test_split.

After that, I trained the model using fit and checked how accurate it is using score.

It gave pretty good accuracy on the test data.

Then I tried predicting some digits using model.predict.

To check how well it predicted, I used confusion_matrix.

In the end, I used seaborn heatmap to show that matrix in a nice and simple way.

So yeah — this code loads the data, shows some digits, splits it, trains the model, predicts, and checks results in a visual way.
