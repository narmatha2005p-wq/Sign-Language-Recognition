# Sign Language Recognition System

A computer vision-based sign language recognition system that detects hand gestures from a live webcam feed and converts recognized gestures into text.

## Project Overview

The Sign Language Recognition System is designed to recognize hand gestures using computer vision and machine learning techniques.

The system captures video through a webcam, detects hand landmarks, processes the extracted features, and identifies the corresponding sign. The recognized gesture is then displayed as text on the screen.

## Objectives

* Recognize sign language gestures using computer vision.
* Process hand gestures from live webcam input.
* Extract useful hand features using landmark detection.
* Provide text output for recognized gestures.
* Develop a simple and user-friendly gesture recognition system.

## Technology Stack

| Category                | Technology       |
| ----------------------- | ---------------- |
| Programming Language    | Python           |
| Computer Vision         | OpenCV           |
| Hand Landmark Detection | MediaPipe        |
| Data Processing         | NumPy, Pandas    |
| Machine Learning        | Machine Learning |
| Version Control         | Git & GitHub     |
| Development Environment | VS Code          |

## System Workflow

```text
Webcam Input
     ↓
Video Frame Capture
     ↓
Hand Detection
     ↓
Landmark Extraction
     ↓
Feature Processing
     ↓
Gesture Recognition
     ↓
Text Output
```

## Key Features

* Real-time webcam input
* Hand landmark detection
* Gesture recognition
* Text-based prediction output
* Live visualization of hand landmarks
* Configurable recognition settings
* Simple and user-friendly interface

## How the System Works

### 1. Video Capture

The system captures live video frames from the webcam using OpenCV.

### 2. Hand Detection

MediaPipe is used to detect the hand and identify important hand landmark points.

### 3. Feature Extraction

The detected landmark information is processed to obtain useful features for gesture recognition.

### 4. Gesture Recognition

The extracted features are provided to the trained classification model to identify the corresponding gesture.

### 5. Text Output

The recognized gesture is displayed as text on the screen in real time.

## Project Structure

```text
Sign-Language-Recognition/
│
├── main.py
├── hand_detector.py
├── gesture_classifier.py
├── utils.py
├── config.py
├── requirements.txt
├── README.md
│
└── data/
    └── gestures/
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/narmatha2005p-wq/Sign-Language-Recognition.git
```

### Navigate to the Project

```bash
cd Sign-Language-Recognition
```

### Create a Virtual Environment

```bash
python -m venv venv
```

### Activate the Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Run the Application

```bash
python main.py
```

Press `q` to exit the application.

## Configuration

Project settings such as detection confidence, frame dimensions, and landmark visualization can be configured through `config.py`.

Example:

```python
CONFIDENCE_THRESHOLD = 0.7
FRAME_WIDTH = 640
FRAME_HEIGHT = 480
SHOW_LANDMARKS = True
```

## Challenges & Solutions

| Challenge                | Approach                                    |
| ------------------------ | ------------------------------------------- |
| Different hand positions | Landmark-based feature extraction           |
| Lighting variations      | Image preprocessing                         |
| Background variations    | Focus on hand landmark information          |
| Recognition errors       | Feature processing and confidence filtering |
| Real-time processing     | Optimized frame processing                  |

## Future Enhancements

* Support for more Indian Sign Language gestures
* Recognition of gesture combinations and phrases
* Text-to-speech output
* Mobile application development
* Multi-language support
* Improved model performance

## Learning Outcomes

Through this project, I gained practical experience in:

* Python programming
* Computer vision
* OpenCV
* MediaPipe
* Machine learning
* Real-time video processing
* Feature extraction
* Git and GitHub

## Author

**Narmatha Pandiyan**

GitHub: https://github.com/narmatha2005p-wq
