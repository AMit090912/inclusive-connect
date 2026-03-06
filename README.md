
# Inclusive Connect


Inclusive Connect is an **AI-powered communication platform** designed to help **deaf and mute individuals communicate with people who do not understand sign language**.

The system detects **American Sign Language (ASL) hand gestures in real time** and converts them into **text captions**, helping bridge the communication gap between sign language users and non-signers.

This project uses **computer vision and machine learning** to make communication more accessible and inclusive.

---

## Problem Statement

Many deaf or mute individuals rely on **sign language** for communication. However, most people do not understand sign language, which creates a **communication barrier** in daily life, workplaces, and education.

Inclusive Connect solves this problem by **automatically detecting sign language gestures and translating them into text in real time.**

---

## Features

* Real-time **hand gesture detection**
* **ASL (American Sign Language) recognition**
* **Gesture to text conversion**
* Webcam-based **real-time processing**
* Simple and easy-to-use interface

---

## Tech Stack

**Programming Language**

* Python

**Libraries & Tools**

* OpenCV
* MediaPipe
* PyAutoGUI
* PyGetWindow
* Pillow

---

## Project Structure

```
inclusive-connect
│
├── Model/                  # Trained gesture recognition model
├── datacollection.py       # Script for collecting gesture training data
├── main.py                 # Main application file
├── Inclusive_connect.mp4   # Project demo video
├── Certificate.pdf         # Project certificate
└── README.md               # Project documentation
```

---

## Installation

Clone the repository:

```
git clone https://github.com/AMit090912/inclusive-connect.git
cd inclusive-connect
```

Install required dependencies:

```
pip install opencv-python mediapipe pyautogui pygetwindow pillow
```

---

## Running the Project

Run the main application:

```
python main.py
```

The webcam will open and start detecting **hand gestures and converting them into text output.**

---

## Dataset Collection (Optional)

To collect gesture training data:

```
python datacollection.py
```

This script captures gesture images using your webcam for training purposes.

---

## Future Improvements

* Support for **multiple sign languages**
* **Speech to sign language translation**
* Integration with **video conferencing platforms**
* Improved **gesture recognition accuracy**
* Web-based application version

---

## Demo

A demo video of the project is included in the repository.

---

## Author

Amit
Computer Science Student
Interested in **AI, Computer Vision, and Backend Development**

---

## License

This project is created for **educational and research purposes**.
