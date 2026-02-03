# Automatic Number Plate Detection and Recognition System

## 📌 Overview
This project is a real-time computer vision application that detects vehicle number plates from a live webcam feed and extracts the license number using Optical Character Recognition (OCR). It uses OpenCV for image processing and a Haar Cascade classifier for number plate detection, followed by Tesseract OCR to recognize the characters on the plate.

The system displays bounding boxes around detected number plates and allows users to save detected plate images using keyboard input.

---

## 🎯 Features
- Real-time number plate detection using webcam
- Bounding box visualization around detected plates
- Extraction of number plate region (ROI)
- Optical Character Recognition (OCR) to read plate numbers
- Save detected number plate images using keyboard input
- Simple and lightweight implementation

---

## 🛠️ Technologies Used
- **Python**
- **OpenCV** – image processing and plate detection
- **Haar Cascade Classifier** – number plate detection
- **Tesseract OCR** – character recognition
- **venv (Virtual Environment)** – dependency isolation

---

## 📂 Project Structure
NO_PLATE_DETECTION/
│
├── number_plate.py
├── model/
│ └── haarcascade_russian_plate_number.xml
├── plates/
│ └── (saved plate images)
├── venv/
└── README.md
