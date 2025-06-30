# Navigation Assistance System for Visually Impaired

## Overview
The Navigation Assistance System is a wearable device designed to aid visually impaired individuals by detecting obstacles and guiding them along safe paths. Using cutting-edge computer vision and audio feedback, this system ensures improved mobility and independence.

## Features
- **Obstacle Detection:** Identifies objects and obstacles in real-time using YOLOv8.
- **Path Guidance:** Detects open pathways for safe navigation.
- **Audio Feedback:** Provides real-time auditory instructions through offline text-to-speech (TTS).
- **Low Latency:** Designed to operate efficiently with minimal delay.
- **Modular Architecture:** Can be extended to include additional sensors (e.g., LiDAR, ultrasonic).

## Project Structure
- **Computer Vision Module:** Detects obstacles and paths using YOLOv8.
- **Audio Feedback Module:** Converts navigation instructions to speech using `pyttsx3`.
- **Live Video Feed:** Processes real-time video input using OpenCV.

## Requirements
- **Hardware:**
  - Raspberry Pi Zero W
  - Camera Module
  - Headphones/Earbuds
- **Software:**
  - Python 3.10+
  - Required Libraries: OpenCV, pyttsx3, YOLOv8

## Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Siddh01110/wearable-navigation-system-visually-impared.git
   cd navigation-assistance-system
