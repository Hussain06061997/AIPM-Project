# Project Overview

## A. DEFINING THE PROJECT

## B. PLANNING THE PROJECT

## C. IMPLEMENTING THE PROJECT PLAN

## D. EXECUTING THE PROJECT
#### Project Design and coding
<p> The first phase of our project involves preparing the dataset for training. We prepare our dataset by loading the images into a Jupyter Notebook file and resizing it using Python. The primary reason for resizing the images is to make easier and faster for the model to train on the image data, because the smaller the size of an image, the shorter the length of training. </p>
<p align="center"><img src="https://github.com/Hussain06061997/Gender-Detection-With-Computer-Vision/blob/master/images/DATAPREP_2.jpg" style="margin: 0 auto;"></p>
<p align="center">Figure 1: The code for data preparation in jupyter notebook</p>
<p>After we finished preparing the data, we stored the images into a .pickle file so that it can be used in a different notebook file that is dedicated to training the model.</p>
<p align="center"><img src="https://github.com/Hussain06061997/Gender-Detection-With-Computer-Vision/blob/master/images/SAVE_IN_PICKLE.jpg"></p>
<p align="center">Figure 2: The code for storing the prepared dataset into a .pickle file</p>
<p> After we have finished preparing the data, we used the TensorFlow library to build a model for the image recognition module. Figure 1 below shows the code for building the Convolutional Neural Network (CNN) model using the Tensorflow Keras library.</p>
<p align="center"><img src="https://github.com/Hussain06061997/Gender-Detection-With-Computer-Vision/blob/master/images/MODEL_FIT.jpg"></p>
<p align="center">Figure 3: The code for building and training the model</p>
<p>The model is then saved into the working directory as a .model file. This .model file will then be used by another program to serve as a backend for our web application</p>
<p align="center"><img src="https://github.com/Hussain06061997/Gender-Detection-With-Computer-Vision/blob/master/images/MODEL_SAVE.jpg"></p>
<p align="center">Figure 4: The code for saving the model into a .model file</p>
<p> Our project is mainly developed using Flask. Flask is a python web development framework. Since our model is written and trained in python. We used Flask as a backend to integrate the model with our web application. This will enable the user to interact with our model via a web application. Figure 1 below shows the python Flask program that serves as the backend for our web application.</p>
<p align="center"><img src="https://github.com/Hussain06061997/Gender-Detection-With-Computer-Vision/blob/master/images/Flask%20AIPM.jpg" style="margin: 0 auto;"></p>
<p align="center">Figure 5: The Flask Program for the project</p>
<p>We also designed a website that serves as the frontend of our application. The website is written in HTML with the CSS Bootstrap Framework. And a few Flask functions are integrated into the HTML to allow for the website to update its content if it receives a response from the model</p>
<p align="center"><img src="https://github.com/Hussain06061997/Gender-Detection-With-Computer-Vision/blob/master/images/HTML1.jpg"></p>
<p align="center">Figure 6: The HTML file for the website and the Flask function</p>
<p align="center"><img src="https://github.com/Hussain06061997/Gender-Detection-With-Computer-Vision/blob/master/images/BEFORE_UPLOAD.jpg"></p>
<p align="center">Figure 7: The web application (before uploading an image)</p>
<p align="center"><img src="https://github.com/Hussain06061997/Gender-Detection-With-Computer-Vision/blob/master/images/AFTER_UPLOAD.jpg"></p>
<p align="center">Figure 8: The web application (after uploading an image and received a response from the model</p>

## E. COMPLETING THE PROJECT

## F. PROJECT PRESENTATION
