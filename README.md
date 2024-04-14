# FaceAttend - Attendance Management System Using Face Recognition

Welcome to FaceAttend, an innovative attendance management system designed to utilize face recognition technology for accurate and efficient tracking of attendance. This system is ideal for educational institutions, workplaces, and events where quick and secure verification of presence is required.

## Key Features

- **Facial Recognition**: Leverages advanced face recognition technology to ensure accurate identification.
- **Real-Time Facial Recognition**: Automatically identifies individuals from a live video feed.
- **Daily Attendance Logs**: Outputs attendance records to a CSV file named with the current date.
- **Pre-loaded with Recognizable Faces**: Includes examples with notable figures like Steve Jobs, Ratan Tata, and Nikola Tesla.
- **Efficient Processing**: Resizes video frames to speed up face recognition processing.
- **Interactive Display**: Shows the live video feed with recognized faces highlighted.
- **Easy to Scale**: Easily add more faces to the system by expanding the known face encodings.


## Technology Stack

This project is built using the following technologies:
- Python 3.10
- OpenCV for facial recognition

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Ensure you have Python 3.x installed, along with the following packages:
- OpenCV
- face_recognition
- numpy

These Python libraries can be installed using pip. Run the following command to install all required libraries:

```bash
pip install opencv-python face_recognition numpy
```
## Installation
To set up this system on your local machine, follow these steps:

1. Clone the repository:
   
   ```bash
   git clone https://github.com/Omkeswani27/FaceAttend.git
   cd FaceAttend
   ```
   - Place the images of individuals you want to recognize in the Images directory. Make sure they are named appropriately (e.g., steve.jpg, Ratan_tata.jpg).
2. Usage:

   - To run the system, execute the following command in the terminal:
   
     ```bash
     python FaceAttend.py
     ```
   - Once started, the system will activate the webcam and begin detecting and recognizing faces in real-time. Attendance for each recognized  individual will be logged in a CSV file named with the current date, stored         in the root directory. To exit the system, press 'q' while the main window is active.
## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## Acknowledgments

- Thanks to Adam Geitgey for the face_recognition library.
- Appreciation to the OpenCV team for their excellent computer vision tools.



