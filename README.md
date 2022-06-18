# Head_Pose_Estimation


![[head]([.gif](https://github.com/ahmed98Osama/Head_Pose_Estimation/blob/main/testing_output.gif))](https://github.com/ahmed98Osama/Head_Pose_Estimation/blob/main/testing_output.gif)


- In this project we will draw the 3 position axis (pitch,yaw,roll) by predicting the 3 angels of each position by training 3 models to predict each angel. 
- We will use [AFLW2000](http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip) dataset with contains 2000 
- We will use MediaPipe library and pycaret in both training and testing phases .
- PyCaret is an open-source, low-code machine learning library in Python that automates machine learning workflows. 


## Steps of the notebook:
    -  Importing Libraries. 
    -  Loading Data. 
    -  Preparing the data for Training.
    -  Prpcessing the Data.
    -  Visualing Random image and drawing its points and axis to select best points
    -  Using pycaret to get best models
    -  Tune and Evaluate the best models (svr , huber) 
    -  Blend them using pycaret 
    -  Defining function for drawing the 3 axis.
    -  Visualing Random image and drawing its points and axis.
    -  Drawing the axis from the true labels on the image.
    -  Testing the model on the image.
    -  Testing the model on a video by processing its frames and drawing the axis on them.

## 🛠 tOOLS USED
Python, pycaret, OpenCV , svr , huber
