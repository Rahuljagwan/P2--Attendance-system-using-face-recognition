
# Attendance Management System using Face Recognition

## Overview
The **Attendance Tracking System** is a Python-driven application that utilizes facial recognition technology to streamline the student attendance process. This project employs OpenCV for detecting and recognizing faces, and incorporates a simple and intuitive graphical interface developed with Tkinter. It offers functionalities for capturing images to train the system, performing real-time facial recognition, and efficiently managing attendance logs.

---

## Features
- **Face Recognition**: Automatically recognize students' faces and mark their attendance.
- **Image Capture**: Capture and save images for training the recognition model.
- **Manual Attendance**: Option to manually fill attendance records.
- **CSV Export**: Generate attendance reports in CSV format.
- **Database Integration**: Store attendance records in a MySQL database.

---

## Technologies Used
- **Python**
- **OpenCV**
- **Tkinter**
- **NumPy**
- **Pandas**
- **MySQL**
- **Pillow**
- **Pyttsx3**

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/attendance-management-system.git
cd attendance-management-system
```

### 2. Install Required Packages
Ensure Python is installed on your system, then install the necessary dependencies:
```bash
pip install -r requirements.txt
```

### 3. Set Up MySQL Database
- Create a MySQL database to store attendance records.
- Update the database connection details in the code as needed.

### 4. Download Haarcascade
Download the Haarcascade XML file for face detection from the [OpenCV GitHub repository] and place it in the project directory.

---

## Usage

### 1. Capture Images
- Run `main_Run.py` to open the GUI.
- Enter the student's enrollment number and name.
- Click on **"Take Images"** to capture their face images.

### 2. Train the Model
- After capturing images, click on **"Train Images"** to train the face recognition model.

### 3. Automatic Attendance
- Select **"Automatic Attendance"** to start the face recognition process using the webcam.

### 4. Manual Attendance
- Use the **"Manually Fill Attendance"** option to manually fill attendance records.

### 5. View Registered Students
- Access the admin panel to view the list of registered students and their details.

---

---

## Contributing
Contributions are welcome! If you have suggestions for improvements or additional features, feel free to fork the repository and submit a pull request.

---

## Acknowledgments
Special thanks to the following:
- **OpenCV** for face detection and recognition functionalities.
- **Tkinter** for GUI development.
- **NumPy** and **Pandas** for data manipulation and analysis.
- **MySQL** for database management.


