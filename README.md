# Automatic_Number_Plate_Recognition_System

## Overview
This project implements an Automatic Number Plate Recognition (ANPR) system using YOLOv11 for object detection and EasyOCR for optical character recognition. The system can detect and extract number plates from images and recognize the text on the plates with high accuracy.

## Features
Real-time Number Plate Detection: Uses YOLOv11 for robust and efficient detection of number plates in various lighting and environmental conditions.
Text Recognition: Employs EasyOCR to extract and decode the characters from detected number plates.
Scalable Solution: Can be extended to include additional features like vehicle tracking or integration with databases.

## System Architecture
Input:
Accepts image files

Detection Stage:
YOLOv11 is used to identify and localize number plates in the input.

Recognition Stage:
Cropped regions of the detected plates are passed to EasyOCR for text extraction.

Output:
Annotated images/videos and recognized plate text are displayed and saved.

## Installation
Prerequisites
Python 3.8 or later
CUDA-enabled GPU (optional, for faster inference)

Clone the Repository
git clone https://github.com/HarshGosula/Automatic_Number_Plate_Recognition_System.git
