# Data-Sprint-6-Face-Mask-Detection

## Objective
As you might be aware, WHO has recommended that even healthy people should wear masks when venturing out of their homes into places where it is difficult to maintain distance from other people. 

Imagine a local housing community has started capturing images of individuals at the entrance/exit gates, public places in and around the housing society. With this image dataset, they want to identify whether an individual in the community has worn a mask or not. Identifying the individuals would further help them to create awareness about the importance of wearing a mask to the specific set of individuals who are not complying to it. Imagine you are leading the efforts to classify images, build a machine/deep learning model to detect face masks.


## About the Data
The training dataset consists of 11,264 medium quality face images belonging to two categories - with_mask (i.e. face is covered with mask) and without_mask (no mask on the face).

Dataset Link: https://drive.google.com/file/d/1_W2gFFZmy6ZyC8TPlxB49eDFswdBsQqo/view?usp=sharing

From the above link you will be able to download a zip file named ‘face_mask_detection.zip’. After you extract this zip file, you will get four files:

train - contains all the images to be used for building the model.

Training_set_face_mask - contains the target value for each of the images in the train folder with their corresponding image name

test - contains all the images for whose the predictions of the labels/target are to be submitted.

Testing_set_face_mask - all the names of the images in the test folder are placed in an order in this csv file. The predictions of the images are to be submitted in the same order as specified in this csv file.

## Evaluation Criteria

Submissions are evaluated using Accuracy Score

<p align="center">
  <img src="https://dphi-courses.s3.ap-south-1.amazonaws.com/Datathons/accuracy_score.png" width="350" title="hover text">
</p>







