# Facial Expression Recognition with Keras
Implementing facial expression recognition using keras and implementing it on a webapp using flask

## Installations
The project has been done using python 3.6. All the package required are mentioned in requirement.txt

## Motivation
The main motivation for doing this project is to use Convolution Neural Network (CNN) to detect the accuracies on the [FER-2013 DataSet](https://www.kaggle.com/deadskull7/fer2013). The aim of the project is to tune the weights of the network to improve the current results and showcase the result using the webapp.

## Using the File
[Facial Emotion Recognition.ipynb](https://github.com/piyush9923/Facial-Expression-Recognition-with-Keras/blob/master/Facial%20Emotion%20Recognition%20.ipynb): To train a new model by changing the architecture of CNN and saving the model in a json file.

[Camera.py](https://github.com/piyush9923/Facial-Expression-Recognition-with-Keras/blob/master/camera.py): Detect the emotion on a video

[Model.py](https://github.com/piyush9923/Facial-Expression-Recognition-with-Keras/blob/master/model.py): Return the Emotion

[Main.py](https://github.com/piyush9923/Facial-Expression-Recognition-with-Keras/blob/master/main.py): Main file containing the code for using the hosting the webapp

## Conclusion
We were able to report an accuracy of 65% although there are scope of improvement.
