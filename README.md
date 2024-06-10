# Automotive Identification of Objects

## Overview
This project showcases a web-based demo that utilizes computer vision to detect and analyze coloured pencils and A4-sized paper in a live video feed from the user's camera. The demo provides real-time predictions of the pencils' colour, length, and position relative to the A4 paper.

## Features
- **Real-time Object Detection:** Detects and analyzes coloured pencils and A4-sized paper in a live video feed.
- **Predictions:** Provides real-time predictions of the pencils' colour, length (in cm), and position.
- **FPS Display:** Displays the frames per second (FPS) to reflect the model's detection speed and performance.
- **Custom Object Detection Model:** Utilizes a custom object detection model trained on a specific dataset.

## Technologies Used
- **HTML, CSS:** For setting up the basic structure and custom styles of the web page.
- **JavaScript Libraries:**
  - **jQuery:** For DOM manipulation.
  - **Lodash:** For utility functions.
  - **Async.js:** For asynchronous operations.
- **Roboflow's JavaScript Library:** For loading and using the custom object detection model.
- **Camera Stream:** Initializes the video stream from the user's camera, focusing on the environment (rear) camera.

## Layout and Style
- **Fullscreen Layout:** Video and canvas elements cover the entire viewport.
- **Dark Theme:** Custom styles ensure a fixed layout with a dark theme.
- **Loading Styles:** Indicate when the model is being loaded.

## Functionality
- **Video Stream Initialization:** Sets up the live video feed from the user's camera.
- **Model Loading:** Authenticates and loads the custom object detection model from Roboflow.
- **Canvas Overlay:** Sets up a canvas overlay on the video to draw bounding boxes and labels for detected objects.
- **Object Detection:** Detects "Paper" and "Pencil" classes, predicting the bounding box for each object.
- **Pencil Height Estimation:** Estimates the height of pencils in centimetres.
- **Responsive Canvas:** Adjusts the canvas size based on the video dimensions.
- **Real-time Rendering:** Renders predictions on the canvas, displaying the pencil's predicted height alongside its class.

## Project Details
- **Duration:** January 2024 to April 2024
- **Guidance:** This project was done under the guidance of Mr. Rajiv Srivastava at Palas Software Pvt Ltd.
- **Team Members:**
  - Aditya Prasad
  - Stanzin Gyalpo
  - Mrinalika Singh






