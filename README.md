# Sign Language Detection

## Overview
This project focuses on detecting basic sign language gestures using computer vision and machine learning. By leveraging the TensorFlow Lite framework and the MediaPipe Holistic Solution, the system is trained to recognize three specific signs:
- **Hello**
- **I Love You**
- **Thanks**

This project is part of my learning journey in applying machine learning to real-world problems, specifically in the domain of accessibility and communication.

## Project Goals
- **Train a TensorFlow Lite Model:**
  - Use labeled landmark data extracted with MediaPipe Holistic Solution to train a lightweight and efficient model for gesture recognition.
- **Gesture Prediction:**
  - Accurately predict the sign language gesture from live video input or pre-recorded videos.
- **Promote Accessibility:**
  - Develop a foundational system that can be expanded to recognize a broader range of signs in the future.

## Methodology
### Data Collection and Preprocessing
- **MediaPipe Holistic Solution:**
  - Extracts key landmarks for hands, face, and body from video frames.
  - Provides robust and accurate pose estimation.
- **Labeled Landmark Data:**
  - Data labeled for each of the three signs to create a training dataset.

### Model Training
- **TensorFlow Lite:**
  - The model was trained on the labeled dataset to classify the gestures efficiently.
  - Optimized for deployment on devices with limited computational resources.

### Inference and Prediction
- **Real-Time Detection:**
  - The system processes live video feeds to detect and classify gestures.
- **Accuracy Optimization:**
  - Iterative testing and adjustment to improve model accuracy and reliability.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- TensorFlow 2.x
- MediaPipe

### Steps
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/sign-language-detection.git
   cd sign-language-detection
   ```

2. **Set Up a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   venv\Scripts\activate   # For Windows
   ```

3. **Run the Application:**
   ```bash
   python app.py
   ```

## Features
- **Gesture Recognition:** Detects and classifies three specific signs: Hello, I Love You, and Thanks.
- **Live Video Input:** Processes real-time video streams for gesture prediction.
- **Efficient Model:** Uses TensorFlow Lite for lightweight and fast inference.

## Acknowledgements
Special thanks to [Nick Nochnack](https://github.com/nicknochnack) for his invaluable tutorials and explanations that guided the development of this project.


