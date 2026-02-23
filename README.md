# Real-Time Stress Detection

## Overview

The **Real-Time Stress Detection System** is a computer vision–based application that estimates a user's stress level using live webcam input and facial landmark analysis. The system processes facial expressions in real time and classifies stress levels into three categories: **Calm**, **Mild**, and **High**.

The application leverages facial landmark detection techniques to analyze subtle facial movements and compute stress-related metrics. Results are displayed through a simple graphical interface that updates continuously.

<img width="1365" height="726" alt="Screenshot_1" src="https://github.com/user-attachments/assets/fbf56250-986c-4939-9858-a622cf034958" />
<img width="1365" height="726" alt="Screenshot_2" src="https://github.com/user-attachments/assets/8dbbe453-08c0-4e9f-8bb9-2fc7da8692a7" />
<img width="1365" height="726" alt="Screenshot_3" src="https://github.com/user-attachments/assets/a2846a08-c334-49bc-a91d-cd6d2d6056f2" />

## Features

* Real-time webcam video processing
* Facial landmark detection using MediaPipe
* Stress-related metric computation, including:

  * Eyebrow elevation
  * Lip tension
  * Head movement (nod detection)
  * Facial symmetry
  * Blink rate
* Real-time stress classification (Calm, Mild, High)
* Graphical visualization of computed metrics


## System Architecture

1. **Video Capture Layer**
   Captures live frames from the user's webcam.

2. **Facial Landmark Detection**
   Uses MediaPipe to extract facial landmark coordinates.

3. **Feature Extraction**
   Computes stress-related metrics based on facial geometry and movement patterns.

4. **Stress Classification**
   Applies rule-based thresholds to determine the stress level.

5. **Graphical Interface**
   Displays metrics and stress classification results in real time.

## Installation and Setup

### 1. Fork the Repository

Click the **Fork** button at the top-right corner of the GitHub repository page to create your own copy.

### 2. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/stress.git
cd stress
```

### 3. Create and Activate a Virtual Environment (Recommended)

```bash
python -m venv .venv
```

* On Windows:

```bash
.venv\Scripts\activate
```

* On macOS/Linux:

```bash
source .venv/bin/activate
```

### 4. Install Dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 5. Run the Application

```bash
python main.py
```

## Requirements

* Python 3.8 or higher
* A functional webcam
* Required Python packages listed in `requirements.txt`

## Project Structure

```
stress/
├──  main.py
├── requirements.txt
└── README.md
```

## Limitations

* Stress detection is based solely on facial expressions and heuristic thresholds.
* The system is not a medical diagnostic tool.
* Accuracy may vary depending on lighting conditions and camera quality.


## Future Improvements

* Machine learning–based stress classification
* Dataset-driven calibration
* Multi-modal stress detection (e.g., heart rate, voice analysis)
* Model performance optimization

## 👤 Author

**HOSEN ARAFAT**  

**Software Engineer, China**  

**GitHub:** https://github.com/arafathosense

**Researcher: Artificial Intelligence, Machine Learning, Deep Learning, Computer Vision, Image Processing**
