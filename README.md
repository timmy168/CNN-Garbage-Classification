# CNN-Garbage-Classification
This is a small project of ultilizing a CNN model to automatic classify the garbage image.

## Training Data
Using garbage image data from Kaggle, with the distribution of 393 images of cardboard、491 images of glass、584 images of paper、472 images of plastic、127 images of trash.
<center><img src="https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/garbage_distribution.png"></center>

Here are the some of the images:
<center><img src="https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/picture.png"></center>

## Flow Chart
<center><img src="https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/system.png"></center>

## Model
Utilize a CNN model with Conv2D, MaxPooling2D, flatten, dense, dropout layers.
<center><img src="https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/model_visual.png"></center>
<center><img src="https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/model_vector.png"></center>

## Accuracy and Loss
<center><img src="https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/accuracy.png"></center>
<center><img src="https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/loss.png"></center>

## Result
The result of finetuing parameters:

<center><img src="https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/result.png"></center>

The result of using different optimizer:

<center><img src="https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/result_2.png"></center>

The confusion matrix of the model:

<center><img src="https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/confusion_matrix.png"></center>

The overall accuracy of the model:
<center><img src="https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/total_accuracy.png"></center>

The result of each categories of the test data:

<center><img src="https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/predict.png"></center>
