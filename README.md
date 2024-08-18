# Deepfake-Audio-Detection-System-Python-SVM

## Overview

The Deepfake Audio Detection System is designed to enhance cybersecurity by accurately detecting manipulated audio content. Utilizing Support Vector Machines (SVMs) and deep neural networks, this project leverages Python, TensorFlow, and librosa for feature extraction to identify and classify deepfake audio. The system provides a user-friendly interface for uploading audio files, training models, and analyzing audio for deepfake detection.

## Table of Contents

- [Project Overview](#overview)
- [Usage](#usage)
- [Features](#features)
- [Screenshots](#screenshots)
- [Technology Stack](#technology-stack)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)


## Usage

1. **Login/Signup**: Users must create an account or log in to access the system's advanced features.
2. **Upload Audio**: Users can upload audio files that they suspect to be deepfakes. The system accepts both genuine and deepfake audio files.
3. **Train Model**: Users can train the model using their uploaded audio data. This enhances the system's accuracy in detecting deepfake audio.
4. **Analyze Audio**: Uploaded audio files are analyzed by the system, and the authenticity of the audio is determined.
5. **View Results**: The system displays whether the audio is genuine or a deepfake, along with a Mel-frequency cepstral coefficients (MFCC) plot to provide a detailed basis for the detection.

## Features

- **Account Management**: Secure login and registration system for personalized access.
- **Audio Upload**: User-friendly file browser interface for uploading audio files.
- **Model Training**: Train the detection model using uploaded audio files.
- **Deepfake Detection**: Analyze and determine the authenticity of audio files.
- **Detailed Results**: Provides a clear result of the analysis along with an MFCC plot.

## Screenshots

### 1. Homepage
![Homepage](images/homepage.png)
*The homepage introduces users to the concept of deepfake audio and its implications. It features a navigation bar with options to log in or register.*

### 2. Login Page
![Login Page](images/login.png)
*The login page allows registered users to securely access their accounts.*

### 3. Signup Page
![Signup Page](images/signup.png)
*The registration page is designed for new users to create an account on the platform.*

### 4. Upload Audio and Model Training Page
![Upload Audio](images/upload_audio.png)
*This page enables users to upload both genuine and deepfake audio files and initiate model training.*

### 5. File Browser for Uploading Audio Files
![File Browser](images/file_browser.png)
*The file browser interface allows users to select audio files from their local storage.*

### 6. SVM Model in PyCharm
![SVM Model](images/svm_model.png)
*The PyCharm IDE showing the creation of the SVM model.*

### 7. Analyze Audio Page
![Analyze Audio](images/analyze_audio.png)
*The analyze audio page allows users to upload and analyze audio files.*

### 8. Result Page
![Result Page](images/result_page.png)
*The output page displays the results of the deepfake audio analysis, including an MFCC plot.*

## Technology Stack

- **Programming Language**: Python
- **Libraries/Frameworks**: TensorFlow, librosa, scikit-learn
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask
- **Database**: SQLite
