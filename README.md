# Social Distancing Detection System

## Overview

This system aims to maintain an organized queue system, preventing crowded queues and ensuring the ease and safety of people. It addresses issues like harassment, surging, and swaying, minimizing the risk of incidents in public spaces. In response to the global catastrophe caused by the spread of the COVID-19 virus, the system also serves as an efficient Social Distance Monitoring tool during pandemics.

## Features

•	Queue Management: Prevents crowded queues, ensuring a smooth and organized flow of people.

•	Harassment Prevention: Mitigates incidents of harassment in public spaces.

•	Social Distance Monitoring: Utilizes YOLOv3 to detect individuals in real-time video feeds, enforcing social separation protocols.

•	Risk Assessment: Indicates the proportions of individuals at High, Low, and No Risk based on their detected separation.

## How It Works

### Object Recognition Paradigm

The framework employs an object recognition paradigm to identify humans in multiple image sequences. The detection model utilizes bounding box information to identify individuals.

### Social Distance Calculation

Using Euclidean distance, the system calculates the pairwise distances of people based on the centroids of their detected bounding boxes. It estimates social distance violations by comparing physical distance to pixel and setting a threshold.

### Tracking Algorithm

A tracking algorithm is employed to detect individuals in video sequences, tracking those who violate/cross the social distance threshold.

### Implementation

•	Tool: Developed using Python, Deep Learning, and Computer Vision.

•	Compatibility: Can be installed in public places and workplaces with uncalibrated RGB cameras.

•	Real-time Monitoring: Monitors social distancing in real-time from CCTV videos.

## Features

•	Human Detection: Uses YOLOv3 to detect humans in the frame.

•	Distance Calculation: Estimates interpersonal distance between detected individuals.

•	Risk Assessment: Identifies and categorizes people as High, Low, or Not at risk.

## Conclusion

The real-time pedestrian detection system for social distancing leverages YOLOv3 to ensure individuals maintain a safe distance. It is user-friendly, easy to deploy, and integrates seamlessly into existing surveillance systems. Privacy and security are prioritized, accommodating variations in pedestrian movement and camera angles. This scalable and efficient system is suitable for various public spaces, contributing to the effective monitoring of social distancing and queue management during pandemics.














































