# Currency and Fake Currency Detection for the Visually Impaired

This project is an Android application aimed at assisting visually impaired individuals in distinguishing between genuine and counterfeit currency. The app uses machine learning and advanced image processing to analyze currency images, converting them into text and providing voice feedback on their authenticity.

## Project Details

### 1. Overview
The application leverages machine learning models and image processing techniques to:
- Analyze real-time images of currency.
- Detect and differentiate between genuine and counterfeit notes.
- Provide voice feedback to users for accessibility.

### 2. Implementation
The project includes:
- A machine learning model for counterfeit detection.
- Advanced image preprocessing techniques to enhance currency features.
- An Android application built using Android Studio for real-time image capture and analysis.

### 3. Dataset
- Source: Custom dataset of real and counterfeit currency images.
- Classes: Genuine and counterfeit currency notes.
- Input Data: High-resolution images of various currency notes.

### 4. Technologies Used
- Programming Language: Java, Python (for model training).
- Libraries and Tools:
  - OpenCV
  - TensorFlow (for model deployment)
  - Android Studio

### 5. File Structure
- currency_detection_app/: Contains the Android application source code.
- model_training/: Scripts for training the machine learning model.
- dataset/: Placeholder for the currency images used for training and testing (not included in the repository).

## Getting Started

### 1. Prerequisites
- Android Studio for application development.
- Python 3.x for model training.
- Required libraries (install via pip for Python scripts):
  pip install tensorflow opencv-python numpy

### 2. Usage
#### 1. Clone this repository:
```bash
git clone https://github.com/vaishakb251/MyProjects.git
```   
#### 2. Open the Android project in Android Studio.
#### 3. Replace the dataset/ directory with your currency images if necessary.
#### 4. Train the model using the scripts provided in the model_training/ directory.
#### 5. Deploy the trained model in the Android application.

## Results
The application provides accurate detection of counterfeit currency, empowering visually impaired users with informed decision-making. Detailed results and model metrics are available in the model_training/ directory.

## Acknowledgements
- Special thanks to contributors and open-source libraries that facilitated this project.
- This project highlights the role of AI in improving accessibility and fraud prevention.

