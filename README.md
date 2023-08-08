# Crowd-Counting
The following project uses concepts of OpenCV and the concept of Crowd Counting Helps count a number of vehicles in the area. This poses huge real-life applications. 


Crowd Counting using OpenCV and Cascade Functions

This repository contains a Python project that performs crowd counting by detecting and counting vehicles in an area using OpenCV and cascade classifiers. The project utilizes image processing techniques to preprocess the images, detect vehicles using cascade classifiers, and visualize the results.


Table of Contents
- Overview
- Installation
- Usage
- Functionality
- Example Results
- Overview

The Crowd Counting project focuses on using OpenCV and cascade classifiers to count vehicles in a given area. The project takes images or a video stream as input, processes the data using various techniques, applies a cascade classifier for vehicle detection, and provides the count of detected vehicles.


- Installation

Clone the repository to your local machine using the following command:

bash
Copy code
git clone https://github.com/Aarjav-2609/Crowd-Counting.git
Navigate to the project directory:

bash
Copy code
cd your-repo-name
Ensure you have the required Python libraries installed. You can install them using pip:

Copy code
pip install opencv-python numpy pillow requests
Usage
Open the Python script crowd_counting.py in your preferred Python environment.

Run the script to initiate the crowd-counting process.

The script demonstrates crowd counting for both images and video streams.


- Functionality

The Crowd Counting project provides the following functionality:

Image Processing: The project uses the Pillow library to load images from URLs and perform basic image processing tasks such as resizing, greyscaling, Gaussian blur, dilation, and morphological operations.

Cascade Classifier: It employs cascade classifiers for vehicle detection. You can provide your own XML cascade classifier files or use the provided ones.

Vehicle Detection: The project detects vehicles in images and videos using the cascade classifiers. Detected vehicles are highlighted with bounding boxes.

Counting: The project counts the number of detected vehicles and displays the count.


- Example Results

The project includes examples demonstrating the crowd-counting process on both images and videos. Images are loaded from URLs and processed to detect vehicles. Detected vehicles are highlighted with bounding boxes, and the count is displayed.
