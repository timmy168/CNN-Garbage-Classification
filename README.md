# CNN-Garbage-Classification
This is a small project of ultilizing a CNN model to automatic classify the garbage image.

## Training Data
Using garbage image data from Kaggle, with the distribution of 393 images of cardboard、491 images of glass、584 images of paper、472 images of plastic、127 images of trash.
![image](https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/garbage_distribution.png)
Here are the some of the images:
![image](https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/picture.png)

## Flow Chart
![image](https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/system.png)

## Model
Utilize a CNN model with Conv2D, MaxPooling2D, flatten, dense, dropout layers.
![image](https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/model_visual.png)
![image](https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/model_vector.png)

## Accuracy and Loss
![image](https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/accuracy.png)
![image](https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/loss.png)

## Result
The result of finetuing parameters:
![image](https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/result.png)

The result of using different optimizer:
![image](https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/result_2.png)

The confusion matrix of the model:
![image](https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/confusion_matrix.png)

The result of each categories of the test data:
![image](https://github.com/timmy168/CNN-Garbage-Classification/blob/main/Picture/predict.png)
