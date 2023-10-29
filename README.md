# Face Recognition App & Attendance System 👤🔍

## Overview

This Python application uses the K-Nearest Neighbors (KNN) algorithm for real-time face recognition. It consists of three separate scripts for different purposes:

- test.py 📷: Captures video, detects faces, and recognizes them using the KNN algorithm. It also records attendance and provides voice feedback.

- addFace.py 📸: Allows users to add faces to the recognition dataset by capturing and storing facial data.

- app.py 🌐: A Streamlit web application for displaying attendance data and implementing conditional logic for "FizzBuzz" counting.

## Features

- Real-time Face Recognition 📹
- Train and Test the KNN Model 🚀
- Record and Display Attendance 📊
- Web Interface for Attendance Data Visualization 🌐
- "FizzBuzz" Counting (in the Streamlit app) 🎉

## Getting Started

1. Clone this repository to your local machine.
2. Ensure you have the necessary dependencies installed, including OpenCV, NumPy, Scikit-learn, and Streamlit.
3. Run the test.py script to start face recognition.
4. Use the addFace.py script to add new faces to the recognition dataset.
5. Access attendance data through the app.py Streamlit (streamlit run app.py) web application.

   - Run add face file
   - Run test file and take attendance
   - Run streamlit run app.py


## Usage

- **test.py 📷**: Run this script to perform real-time face recognition. Press 'O' to capture attendance and save it to an Excel sheet, and press 'Q' to exit.

- **addFace.py 📸**: Use this script to capture and store facial data for recognition. It records 30 samples per person.

- **app.py 🌐**: Start the Streamlit app to visualize attendance data. Conditional "FizzBuzz" counting is also implemented in the app.

## Data Files

- Face data and label data are stored in 'data/names.pkl' and 'data/faces_data.pkl', respectively. These files are automatically created and updated as needed.

## Screenshots

![face](https://github.com/HarshBaldaniya/Face-Detection/assets/89580214/9eb80a8b-99c1-4715-9992-0a45aaa65cb1)
![output](https://github.com/HarshBaldaniya/Face-Detection/assets/89580214/e077ad42-b2e6-475c-9c40-68bd263e5507)



## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.harshbaldaniya.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hb134/)

Enjoy using the Face Recognition App! 😃🚀
