# Facial Gesture Detection

This project detects facial gestures such as blinking, smiling, eyebrow raises, and pimples using OpenCV and dlib in Python. It uses dlib’s 68 facial landmark detector model to analyze facial features in real time via your webcam.

---

## Features

- Detects eye blinks using Eye Aspect Ratio (EAR)
- Detects mouth open/close using Mouth Aspect Ratio (MAR)
- Detects eyebrow raises by measuring eyebrow-to-eye distances
- Simple pimple/redness detection on the face
- Visualizes facial landmarks and detected gestures on video feed

---

## Prerequisites

- Python 3.6 or higher
- Webcam connected to your computer

---

## Setup Instructions

### 1. Clone or download this repository

```bash
git clone https://github.com/prateeksatyal/facial-gesture-detection.git
cd facial-gesture-detection
