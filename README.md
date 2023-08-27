# TASK: You need to run Activity recognition using pose estimation on this video:.


This repository contains code and instructions for performing activity recognition using the I3D Kinetics-400 model on video data. The I3D model is a deep learning architecture that has been pre-trained on a large video dataset and is capable of recognizing a wide range of human actions and activities.


 #  Introduction
Activity recognition is the process of identifying and categorizing human actions or activities within video data. The I3D Kinetics-400 model is a powerful deep learning model designed for this purpose. It has been trained on a dataset containing 400 different activities, enabling it to predict actions and their corresponding probabilities from video frames.

Prerequisites
Before you begin, ensure you have the following:

Python (>=3.6)
Required packages: tensorflow, tensorflow_hub, numpy, cv2, imageio, IPython
Access to the internet to download the model and video data
Getting Started
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/Ali-Debug/activity-recognition-i3d.git](https://github.com/Ali-Debug16/Kaiburr-Task6/blob/main/Activity%20recognition%20using%20pose%20estimation.ipynb)
Navigate to the project directory:

bash
Copy code
cd activity-recognition-i3d
Install the required packages. You can use the following command:

bash
Copy code
pip install -r requirements.txt
Usage
Run the Jupyter Notebook provided in the repository (activity_recognition_i3d.ipynb) using Jupyter or JupyterLab.

The notebook guides you through the following steps:

Fetching a random video from the UCF101 dataset.
Loading and processing the video frames.
Predicting activities using the I3D Kinetics-400 model.
Displaying the top predicted activities along with their probabilities.
Sample Video Analysis
The notebook includes sample video analyses to showcase the model's activity recognition capabilities. It demonstrates how to load video frames, make predictions, and display the results. The results are presented as the top predicted activities along with their corresponding probabilities.

Contributing
Contributions to this project are welcome. If you have any suggestions, improvements, or bug fixes, feel free to submit a pull request.


2. Convert the product classes into numbers using label encoding.
3. Create a conventional machine learning model to complete the task. Since this is NLP, hence we have chosen to work with truncated data.
