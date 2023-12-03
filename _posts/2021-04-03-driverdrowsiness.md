---
layout: posts
title:  "Real-Time Driver Drowsiness Detection"
date:   2021-04-03 18:59:00 +0000
categories: work
highlight_home: true
tags: AI Python
header:
 overlay_image: "https://th.bing.com/th/id/OIP.GLg_NE90q71wgKc6mE0fdQHaE8?rs=1&pid=ImgDetMain"
 teaser: "https://th.bing.com/th/id/OIP.GLg_NE90q71wgKc6mE0fdQHaE8?rs=1&pid=ImgDetMain"
 caption: "Credit: https://robertdebry.com/dangers-drowsy-driving/"
---
Using Convolutional Neural Networks

> To review the code for this project, visit [Real Time Driver Drowsiness Detection on GitHub](https://github.com/nidhi-u/RealTimeDriverDrowsinessDetection)

### Introduction
One of the most prevailing problems across the globe today is the booming number of road accidents. Driver's drowsiness or lack of concentration is considered as a dominant reason for such mishaps. This project therefore proposes an approach to implement a driver drowsiness alert system which would calculate the driver's sleepiness and prevent such accidents caused by the same.
<br>
<br>
By capturing visual information of the driver and using this behavioral data with AI, we have developed a real-time drowsiness detection system based on Convolutional Neural Networks (CNNs). Here, we create a classification network to determine if the driver's eyes are closed and whether the driver is yawning. The system capture's the driver's images and examines eye and mouth positions and uses this data and our CNN model to detect fatigue. Continuously monitoring the driver's state, as soon as the driver indicates drowsiness, the system sounds an alarm to alert the driver.

### Data Flow and Process Descriptions
![Data Flow Diagram](/assets/images/driverdrowsiness/drowsiness1.png)
<br>
Pertinent Processes:
1) Collect input: It takes in video feed from the user's device and breaks it down to frames for further processing.
<br>
2) Convert to Grayscale: Convert each individual video frame to grayscale.
<br>
3) Resize Image: Resize the image to a uniform dimension.
<br>
4) Face and Eye Detection: From the processed image, detect face and eye in the given frame.
<br>
5) Crop image: After facial parts crucial to the algorithm have been detected, we crop the rest out.
<br>
6) Detecting Drowsiness: We feed these optimally cropped images to our detection models to detect drowsiness levels.
<br>
7) Train Eye and Yawn Classifier Model: Train the model to classify yawn from no_yawn and eye open or close.
<br>
8) Determine Drowsiness Level against Threshold: After detecting the drowsiness level of the user, the system compares it to the decided threshold value.
<br>
9) Alarm Ringer: If the drowsiness level crosses the decided threshold, the drowsiness has reached a critical value and the system rings out an alarm to alert the driver.

### Conclusion
Thus, this real-time system utilizes a webcam to capture images continuously and meaure the state of the driver according the to specified algorithm and give a warning when required. The user must have access to a device with a working camera and must grant the application the permission to access the same.
<br>
<br>
<br>
<br>
<br>