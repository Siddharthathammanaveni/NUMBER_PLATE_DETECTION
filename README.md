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

---

## ⚙️ Installation & Setup

### 
1️⃣ Create and activate virtual environment
python -m venv venv
venv\Scripts\activate
2️⃣ Install required libraries
pip install opencv-python pytesseract
3️⃣ Install Tesseract OCR (Windows)
Download from: https://github.com/UB-Mannheim/tesseract/wiki

During installation, select Add to PATH

▶️ How to Run the Project
python number_plate.py
⌨️ Controls
s → Save detected number plate image

ESC → Exit the program

🔄 Working Flow
Capture live video from webcam

Convert frame to grayscale

Detect number plate using Haar Cascade

Draw bounding box around plate

Extract plate region (ROI)

Preprocess image for OCR

Extract text using Tesseract OCR

Display and save results

🧪 Applications
Traffic monitoring systems

Automated parking systems

Toll booth automation

Vehicle identification systems

Smart city applications

⚠️ Notes
Detection accuracy depends on lighting and camera quality

Haar Cascade works best for frontal and clear number plates

OCR accuracy improves with proper preprocessing

🎓 Project Description (Short)
This project demonstrates real-time vehicle number plate detection and recognition using OpenCV and OCR techniques for intelligent transportation systems.
