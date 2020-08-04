# Facial_Expression_Recognition
This repository contains code and it's description for Facial Expression Recognition.

Download the dataset from here:- https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset

The code writeen is for running the facial recognition on the browser.
The following are the steps that one needs to follow:

1) Clone the repository and download the dataset from the link.

2) For training I have included both .ipynb and .py file which are used for training. The .ipynb file also contains discription of all the steps.
For my specific requirement I have set the hyperparameters as I needed, one can always change them for better accuracy. Also you are free to contribute here.

3) I have included the weights so if you are not retraining the model, run the **main.py** file.

4) After the main.py runs successfully, open your browser and visit: 127.0.0.1/5000 (localhost)

** Note:-** One important thing to note is that if you want to detect facial expression through your web-camera in the browser, you will have to make a change in the **camera.py ** file. On line 11 in the code you will have to write the following: ** self.video = cv2.VideoCapture(0) **. And if you want to detect facial expression from a video than you will have to specify the path to the video instead of '0'.
  

