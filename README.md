# 📸 Automated Attendance System

A **contactless, real-time attendance system** built using face recognition technology. This project leverages computer vision and a web-based interface to automate attendance tracking efficiently and accurately.

---

## 🚀 Overview

Traditional attendance systems (manual registers, RFID cards, fingerprint scanners) are often:

* Time-consuming
* Error-prone
* Easy to manipulate
* Not hygienic (post-pandemic concerns)

This project solves these issues by using **face recognition** to automatically detect and mark attendance in real time.

---

## ✨ Features

* ✅ Contactless attendance using face recognition
* ⚡ Real-time processing and updates
* 🧠 Accurate detection using trained models
* 🌐 User-friendly web interface
* 📊 CSV-based attendance storage
* 🔒 Secure local data handling
* 🚫 Prevents duplicate attendance entries

---

## 🛠️ Technologies Used

* **OpenCV**

  * Face detection (Haar Cascade)
  * Face recognition (LBPH algorithm)

* **Streamlit**

  * Interactive web interface
  * Live camera integration
  * Attendance display

---

## 🧩 System Architecture

The system consists of two main components:

### 1. Face Recognition Engine

* Detects faces using Haar Cascade Classifier
* Recognizes individuals using LBPH model

### 2. Web Interface

* Built with Streamlit
* Allows users to:

  * Start recognition
  * View attendance
  * Download records

---

## ⚙️ How It Works

### 1. Data Collection & Training

* Collect face images of users
* Label each image with an ID/name
* Train LBPH recognizer model

### 2. Face Detection

* Capture live video via webcam
* Detect faces in each frame

### 3. Face Recognition

* Compare detected faces with trained dataset
* Identify individuals with confidence threshold

### 4. Attendance Marking

* Log:

  * Name/ID
  * Date
  * Time
* Prevent duplicate entries

### 5. Data Storage

* Store attendance in CSV file
* Display in Streamlit dashboard

---

  * Contact form (via webhook integration)

---

## 👩‍💻 Author

**Muzna Kamal**
BSEE, National University of Computer & Emerging Sciences (FAST-NUCES), Karachi

---

## 📜 License

This project is for academic and educational purposes.

---

