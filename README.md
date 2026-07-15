# Face Recognition Attendance System

An automated attendance tracking system leveraging facial recognition technology to identify individuals in real-time.

## Features

- **Real-Time Recognition**: Detects and identifies faces using a webcam or video feed.
- **Automated Attendance**: Logs attendance directly to a database or spreadsheet upon successful identification.
- **High Accuracy**: Utilizes modern computer vision models for precise facial recognition.
- **Admin Dashboard**: (If applicable) View and manage attendance records easily.

## Tech Stack

- Python
- OpenCV
- face_recognition (or similar deep learning libraries)
- Backend (Flask/Django/FastAPI or direct file writing)

## Setup & Installation

1. Clone the repository: `git clone https://github.com/wasim-builds/face-recognition-attendance-system.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the main application script (e.g., `python main.py` or `app.py`).

## Usage

1. Register new faces by adding their images to the designated `known_faces` directory.
2. Start the application to begin the real-time webcam feed.
3. The system will automatically detect faces and mark attendance.

## License

This project is licensed under the MIT License.
