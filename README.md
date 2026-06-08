# 🔐 Face Recognition Smart Door Access Control System

An AI-powered Smart Door Access Control System that uses facial recognition to identify authorized users and automatically grant or deny access. This project combines Computer Vision and Machine Learning techniques to create a secure and intelligent authentication system.

## 📌 Overview

Traditional authentication methods such as keys, cards, and passwords can be lost, stolen, or shared. This project addresses these limitations by using facial recognition as a biometric authentication mechanism.

The system detects faces, extracts facial features, compares them with stored authorized users, and determines whether access should be granted or denied.

---

## 🚀 Features

- Face Registration and Enrollment
- Face Detection and Encoding
- Authorized User Database Creation
- Face Matching and Verification
- Access Grant/Deny Decision System
- Confidence Score Calculation
- Image-Based Face Recognition
- Video-Based Face Recognition
- Performance Evaluation
- Interactive Testing Interface
- Google Drive Dataset Integration

---

## 🛠️ Technologies Used

- Python
- OpenCV
- Face Recognition Library
- NumPy
- Matplotlib
- TensorFlow
- DeepFace
- Pickle
- Google Colab

---

## 📂 Project Structure

```text
Face-Recognition-Smart-Door/
│
├── authorized/
│   ├── person1.jpg
│   ├── person2.jpg
│
├── test_images/
│   ├── test1.jpg
│   ├── test2.jpg
│
├── face_data.pkl
├── FACE_RECOGNATION.ipynb
├── README.md
└── results/
```

---

## ⚙️ How It Works

### Step 1: Register Authorized Users

Upload images of authorized individuals.

```python
person_name = "Haider"
```

The system extracts facial features and generates unique face encodings.

---

### Step 2: Create Face Database

All face encodings are stored in a database file.

```python
face_data.pkl
```

This enables fast retrieval and matching during authentication.

---

### Step 3: Face Recognition

When a new image or video is provided:

1. Face is detected.
2. Face encoding is generated.
3. Encoding is compared with stored encodings.
4. Similarity score is calculated.
5. Access decision is made.

---

### Step 4: Access Control

If the face matches an authorized user:

```text
ACCESS GRANTED 🔓
```

Otherwise:

```text
ACCESS DENIED 🔒
```

---

## 📊 Performance Evaluation

The project includes an evaluation module that measures recognition performance using:

- Accuracy Calculation
- Confidence Score Analysis
- Recognition Visualization

---

## 📷 Sample Output

```text
Name: Haider
Confidence: 92.5%
Status: ACCESS GRANTED 🔓
```

```text
Name: Unknown
Confidence: 34.7%
Status: ACCESS DENIED 🔒
```

---

## 🎯 Applications

- Smart Home Security
- Office Access Control
- Attendance Management Systems
- Identity Verification Systems
- AI-Based Surveillance
- Restricted Area Monitoring

---

## 🔮 Future Improvements

- Real-Time Webcam Recognition
- Liveness Detection (Anti-Spoofing)
- Database Integration (MySQL/PostgreSQL)
- Multi-Factor Authentication
- Mobile Application Integration
- Cloud-Based Access Logs
- Face Mask Detection
- Real-Time Monitoring Dashboard

---

## 📈 Results

The system successfully:

- Detects faces from images and videos
- Identifies authorized users
- Prevents unauthorized access
- Provides confidence-based verification
- Demonstrates practical use of AI in security systems

---

## 👨‍💻 Author

**Haider Sattar**

Artificial Intelligence Student

Email: haidersattar810@gmail.com

Location: Pakistan

---

## 📄 License

This project is developed for educational and research purposes. Feel free to use and modify it for learning and academic projects.

⭐ If you found this project useful, consider giving it a star on GitHub.
