# Object Detector Demo

The Object Detector is a web-based application that utilizes a machine learning model to detect multiple objects in real-time using a webcam. This project leverages the COCO-SSD model and TensorFlow.js to enable in-browser object detection, allowing users to see detected objects highlighted with bounding boxes and labeled with their classification and confidence score.

![Object Detector](https://github.com/yerin16/object-detector/blob/main/images/preview.png?raw=true)


## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [How it works](#how-it-works)

## Features

- **Real-Time Object Detection:** Utilizes a webcam to identify and classify objects in the video feed.
- **COCO-SSD Model:** Pre-trained model that can detect a wide range of objects, such as people, cars, and animals.
- **Live View:** Displays bounding boxes around detected objects, along with labels and confidence percentages.
- **User-Friendly Interface:** A simple and clean layout designed using HTML, CSS, and Bootstrap, ensuring ease of use.

## Technologies Used

- **TensorFlow.js:** Enables the running of machine learning models directly in the browser.
- **COCO-SSD Model:** Pre-trained object detection model used for recognizing and classifying objects in the video stream.
- **HTML/CSS/JavaScript:** Used to build the website interface and manage functionality.
- **Bootstrap:** For responsive and clean design.

## File Structure
- **index.html:** The main webpage, providing the user interface for the object detection system(index).
- **style.css:** Contains the styling for the layout and webcam display elements(style).
- **script.js:** Implements the logic for accessing the webcam, loading the COCO-SSD model, and handling object detection in real-time(script).

## How It Works

1. The user activates the webcam by clicking the "Get Started" button on the web interface.
2. The application loads the COCO-SSD model in the background.
3. Once the model is ready, the webcam feed is processed, and objects within the frame are identified.
4. Bounding boxes with labels and confidence percentages are drawn on the live video feed to indicate detected objects.
5. The detection process continues in real-time, updating as the webcam captures new frames.