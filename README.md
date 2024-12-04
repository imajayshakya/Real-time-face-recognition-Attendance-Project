# FaceAttendanceProject

## Overview
The **FaceAttendanceProject** is a Python-based application designed for recognizing faces and marking attendance using OpenCV. The project uses a dataset of facial images and provides a simple command-line interface to process and record attendance efficiently.

---

## Features
- **Dataset Creation**: Capture and store facial images to build a dataset for recognition.
- **Facial Recognition**: Recognize faces in real-time and mark attendance automatically.
- **Easy to Use**: Simple CLI commands for managing dataset creation and recognition processes.
- **Cross-Platform**: Compatible with Windows, macOS, and Linux environments.

---

## Prerequisites
Ensure the following are installed on your system:
- **Python**: Version 3.7.6 or higher.
- **OpenCV**: Version 3.3.0 or higher.

### Install Required Libraries
Use the following pip commands to install necessary dependencies:

```bash
pip install opencv-contrib-python numpy
```

---

## Installation Guide

1. Clone or download this repository to your local machine.
2. Navigate to the project directory:

   ```bash
   cd FaceAttendanceProject
   ```

3. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Verify the installation by running the following command:

   ```bash
   python --version
   ```

   Ensure the version matches the prerequisites.

---

## Usage Instructions

### Step 1: Create Dataset
Run the `Dataset.py` script to create a dataset of facial images:

```bash
python Dataset.py
```

- Follow the on-screen prompts to capture facial images.
- Ensure proper lighting and positioning during image capture.
- Images will be saved in a designated dataset folder.

### Step 2: Recognize Faces and Mark Attendance
Run the `reco.py` script to recognize faces and write attendance to a log file:

```bash
python reco.py
```

- The application will open a window showing the video feed.
- Recognized faces will be marked in the attendance log.
- Attendance records will include the timestamp of recognition.

### Stop the Program
To close the window and stop the program, press `Ctrl+C` in the terminal.

---

## Directory Structure
```
FaceAttendanceProject/
|
├── Dataset.py          # Script for creating the dataset.
├── reco.py             # Script for facial recognition and attendance.
├── requirements.txt    # List of required Python libraries.
├── dataset/            # Folder where facial images are stored.
└── README.md           # Project documentation (this file).
```

---

## Troubleshooting

1. **OpenCV Installation Errors**:
   - Use the following alternative command to install OpenCV:
     ```bash
     pip install opencv-python-headless
     ```
---

## Future Enhancements
- Support for multiple datasets and user profiles.
- Improved recognition accuracy with deep learning models.
- Integration with cloud storage for attendance logs.

---

## Contact
For any queries or suggestions, feel free to reach out to the project maintainer at:
- **Instagram**: @mobi_cam_pics
- **GitHub**: [Project Repository](https://github.com/imajayshakya/Real-time-face-recognition-Attendance-Project)

