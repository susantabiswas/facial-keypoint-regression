# <u>Facial Keypoint Detection</u>

I have made a Facial Keypoints Regressor that regresses the keypoints for human face. This keypoint detection problem is a regression problem since we are predicting the coordinates for the landmarks on the face which are real numbers. 
Detection of facial keypoints is very useful for a number of tasks like facial recognition, detection etc. The keypoints selected in this code uses 15 keypoints representing the various coordinates on the human face. 
The dataset for this problem was downloaded from Kaggle https://www.kaggle.com/c/facial-keypoints-detection/. 

CNN was used for this problem. The model achieved an accuracy of 76% on the validation set. The model was trained on a set of approx 1700 images and around 300 images were taken for validation purpose. The images were grayscale and had shape 96 X 96. 

## Model Performance on real world data
Predictions for some real world color images.

<img src ='images/1.png'  width="330" height="380">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src ='images/4.png'  width="380" height="380">

<img src ='images/6.png'  width="330" height="480">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src ='images/5.png'  width="520" height="390">


## Model Performance on Validation data
Predictions for some validation images.
![validation](images/snap.png)

## Model Architecture
The model uses a CNN based Architecture.
<p align="center">
  <img src ='images/model_plot.png'  width="321" height="1000" >
</p>

### References
Dataset downloaded from Kaggle https://www.kaggle.com/c/facial-keypoints-detection/. 
