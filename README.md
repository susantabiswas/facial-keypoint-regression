# <u>Facial Keypoint Detection</u>
Detection of facial keypoints is very useful for a number of tasks like facial recognition, detection etc. The keypoints selected in this code uses 15 keypoints representing the various coordinates on the human face. 
The dataset for this problem was downloaded from Kaggle https://www.kaggle.com/c/facial-keypoints-detection/.

This keypoint detection is a regression problem since we are predicting the coordinates for the landmarks on the face. CNN was used for this problem. The model achieved an accuracy of 76% on the validation set.

## Model Performance on real world data
<img src ='images/1.png'  width="330" height="380">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src ='images/4.png'  width="380" height="380">

<img src ='images/6.png'  width="330" height="480">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src ='images/5.png'  width="520" height="390">



### Model Architecture
<img src ='images/model_plot.png'  width="321" height="1000">
