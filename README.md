# BrickShapeRecognitionModel
A neural network model based on TensorFlow that predicts shape of brick

# Problem definition

A model needs to recognize following brick shapes:
- 'bruk_prosty'
- 'master'
- 'metro'
- 'metro_xl'
- 'podwojne_t'
- 'trend'
- 'wena'

In order to do this I converted all brick images into grayscale and gave it to neural network.

Here are some sample images:

![](https://github.com/Kamelleon/BrickShapeRecognition/blob/main/sample_images/bruk_prosty%20(4).jpg)

![](https://github.com/Kamelleon/BrickShapeRecognition/blob/main/sample_images/master.jpg)

![](https://github.com/Kamelleon/BrickShapeRecognition/blob/main/sample_images/metro%20(3).jpg)

![](https://github.com/Kamelleon/BrickShapeRecognition/blob/main/sample_images/wena.jpg)

Model resulted in 99% accuracy on validation set and 100% on test set that had 30 images.
