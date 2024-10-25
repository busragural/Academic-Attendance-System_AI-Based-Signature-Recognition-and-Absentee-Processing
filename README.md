# Academic Attendance System: *AI-Based Signature and Absence Detection*

<p align="center">
  <img src="https://github.com/user-attachments/assets/899d0aa1-8475-48e6-90d6-153828dd6986" width="270" height="480" alt="App GUI">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/56e3adca-ad81-45eb-a799-4297fbca7d52" width="270" height="480" alt="App GUI">
</p>

## Overview  
This project introduces an AI-powered mobile application for automating academic attendance. Developed by a two-person team, it offers efficient management of attendance sheets by recognizing signatures, detecting fraudulent entries, and tracking student absences. The system enhances the accuracy of attendance records and significantly reduces the workload of instructors.

## Project Description  
This system leverages machine learning techniques and image processing tools to digitize and validate attendance records from physical sheets. Key processes include signature comparison using neural networks and automated tracking of students' attendance data. It is designed for seamless integration with both Android and iOS platforms, ensuring a broad reach and user-friendly experience for academic professionals.

### Objectives
1. **Signature Recognition and Fraud Detection:** Uses CNN and SNN models to match signatures and identify inconsistencies.
2. **Automated Absence Tracking:** Captures attendance from scanned sheets and records student absences in real time.
3. **User Notifications:** Notifies students who approach or exceed absence limits.
4. **Cross-Platform Compatibility:** Supports both Android and iOS devices through React Native.

## Features  
- **AI-Powered Signature Matching:** Automates the detection of fraudulent signatures.
- **Automated Attendance Processing:** Simplifies tracking and storing absence data.
- **Notifications:** Alerts students and instructors about attendance updates.
- **Cloud Database Integration:** Utilizes MongoDB for efficient data management.
- **User-Friendly Interface:** Easy upload of attendance sheets with real-time feedback.

## Technologies
- **Frontend:** React Native, Expo
- **Backend:** Flask API for image analysis and processing
- **Machine Learning Models:** CNN, SNN implemented with TensorFlow and Keras
- **Database:** MongoDB for secure storage of attendance records
- **Image Processing Libraries:** OpenCV, NumPy for preprocessing and feature extraction
- **Visualization Tools:** Matplotlib, Seaborn

## System Requirements  
- **Operating Systems:** Android 8.0+ / iOS 11+
- **RAM:** Minimum 2 GB (Recommended 4 GB)
- **Camera:** At least 8 MP for optimal image capture
- **Storage:** 4 GB minimum, 8 GB recommended

## How It Works  
1. **Attendance Sheet Upload:** Instructors upload a photo of the attendance sheet via the app.
2. **Signature Matching:** The system analyzes and compares signatures using pre-trained models.
3. **Absence Calculation:** Absences are automatically tracked and updated in the database.
4. **Notifications:** Alerts are sent to students with critical absence records, and detailed reports are available for instructors.

## Contributors
- Büşra Güral
- Emir Oğuz
