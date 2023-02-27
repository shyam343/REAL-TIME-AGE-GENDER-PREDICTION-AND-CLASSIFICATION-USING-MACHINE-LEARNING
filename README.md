# REAL-TIME-AGE-GENDER-PREDICTION-AND-CLASSIFICATION-USING-MACHINE-LEARNING.
![fon](https://user-images.githubusercontent.com/84222697/221489885-996b24ac-81ba-47f4-9574-708ccc8da25f.jpg)

## OBJECTIVE:-
The objective of real-time age-gender prediction and classification using machine learning is to accurately predict the age and gender of a person in real-time based on visual input.
## About The Project:-
This is a Machine Learning-based Project that uses computer vision techniques to predict and classify the age and gender of a person in real-time based on visual input from a camera or video feed.The predicted gender may be one of ‘Male’ or ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). The system typically involves training a machine learning model on a large dataset of images or videos labeled with age and gender information, and then using the trained model to make predictions on new, unseen images or videos. Applications of this technology include marketing, security, and healthcare.
## DataSet:-
For This Machine Learning Project I had used the Adience dataset; The dataset is available in the public domain and you can find it [Here](https://www.kaggle.com/datasets/jangedoo/utkface-new) . UTKFace dataset is a large-scale face dataset with long age span (range from 0 to 116 years old). The dataset consists of over 20,000 face images with annotations of age, gender, and ethnicity. The images cover large variation in pose, facial expression, illumination, occlusion, resolution, etc. This dataset could be used on a variety of tasks, e.g., face detection, age estimation, age progression/regression, landmark localization, etc.

## Additional Python Libraries Required :
+ OpenCV
```ruby
pip install opencv-python
```
- argparse
```ruby
pip install argparse
```

## The contents of this Project :
+ opencv_face_detector.pbtxt
- opencv_face_detector_uint8.pb
+ age_deploy.prototxt
/ age_net.caffemodel
* gender_deploy.prototxt
+ gender_net.caffemodel
- a few pictures to try the project on
+ detect.py

For face detection, we have a .pb file- this is a protobuf file (protocol buffer); it holds the graph definition and the trained weights of the model. We can use this to run the trained model. And while a .pb file holds the protobuf in binary format, one with the .pbtxt extension holds it in text format. These are TensorFlow files. For age and gender, the .prototxt files describe the network configuration and the .caffemodel file defines the internal states of the parameters of the layers.

## Working:
