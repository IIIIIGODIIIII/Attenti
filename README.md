# Attenti
Attenti is an AI-based attendance system designed to streamline the process of taking attendance using face recognition technology. The system leverages computer vision and machine learning techniques to accurately identify individuals and mark their attendance.

## Features
1. Face Recognition: Uses cv2 and face_recognition libraries for detecting and recognizing faces.
2. Attendance Logging: Records attendance data in a CSV file.
3. Real-time Processing: Captures video from a webcam and processes frames in real-time.

## Installation
1. Clone the repository:

   ```bash
    git clone https://github.com/IIIIIGODIIIII/Attenti.git
    cd Attenti
   
2. Install the required dependencies:

   ```bash
   pip install opencv-python face-recognition

## Usage
1. Run the attendance script:
    ```terminal
    python attendance.py
2. The system will start capturing video from the webcam and recognize faces.

## Files
1. attendance.py: Main script to run the attendance system.
2. Attendance.csv: File where attendance records are stored.
3. photos/: Directory containing reference images for face recognition.

