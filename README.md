# Facial expressions detection
## This project detects facial expressions of humans using Deep Learning and Computer Vision

### Here's a snippet

![expression_detection](https://user-images.githubusercontent.com/61016383/94587769-afa85680-02a0-11eb-897f-ffe8d88becbe.gif)

## About Project
  
  - #### Using [TensorFlow](https://www.tensorflow.org/), I have created a deep learning ConvNet Model `detection_model.h5` to detect Happy, Sad, Angry and Surprised expressions.
  
  
  - #### The model is trained on the [FER-2013 Kaggle Dataset](https://www.kaggle.com/msambare/fer2013).
  
  
  - #### You can find the model building and training process in the `model_building.ipynb` file.
  
  
  - #### Using OpenCV and Python, I have extracted the facial features with the help of Haar Cascade Classifier `haarcascade_frontalface_default.xml`, and given them to my Model to detect the expressions.
  
  
  - #### I have written two Python scripts viz. `detection_on_vid.py` and `detection_on_image.py`. The former detects facial expressions using Webcam and the latter detects the    expressions of human faces in an image. 
  
  
## Libraries Used

  - #### TensorFlow 2.0
  
  - #### Keras
  
  - #### OpenCV
  
  - #### Python>=3.7
  
  - #### Numpy
  
  
