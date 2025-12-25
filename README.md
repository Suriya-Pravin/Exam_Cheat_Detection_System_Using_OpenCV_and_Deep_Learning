## 🧠 Exam Cheat Detection System Using OpenCV and Deep Learning
### Small Description

The AI-Based Intelligent Exam Proctoring and Cheating Detection System is designed to monitor students during examinations using computer vision techniques. The system analyzes real-time webcam footage to detect suspicious behaviors such as frequent looking around or leaning movements and automatically logs evidence to ensure exam integrity.

## 📘 About

The AI-Based Intelligent Exam Proctoring System leverages computer vision and deep learning to automate the invigilation process during online or computer-based examinations. Traditional exam monitoring methods rely heavily on human supervisors, which can be inefficient, error-prone, and difficult to scale.

This project uses a real-time object detection model to identify students and analyze their behavioral patterns over time. Suspicious actions sustained beyond a predefined duration are flagged as potential cheating incidents. The system records visual evidence and maintains logs for further review, thereby enhancing fairness and transparency in examinations.

## ✨ Features

Real-time student detection using deep learning.

Temporal behavior analysis to reduce false positives.

Color-coded visual alerts for easy monitoring.

Automatic cheating evidence capture (image-based).

Timestamped CSV log generation.

Modular and scalable system design.

Configurable thresholds for different exam environments.

Works with standard webcams.

## 🛠️ Requirements
Software Requirements

Operating System: Windows 10 / Ubuntu (64-bit)

Programming Language: Python 3.8 or later

IDE / Environment: Jupyter Notebook, VS Code

Libraries & Frameworks

Ultralytics YOLOv8 – real-time object detection

OpenCV – image processing and video handling

NumPy – numerical computations

CSV / OS Modules – logging and file handling

Hardware Requirements

Webcam (minimum 720p recommended)

Minimum 8 GB RAM for smooth execution

## 🧩 System Architecture

The system follows a modular pipeline where each component performs a specific role:

Architecture Flow:

Webcam Input
   ↓
YOLOv8 Person Detection
   ↓
Behavior Classification
   ↓
Temporal Analysis
   ↓
Cheating Decision Engine
   ↓
Evidence Logging & Alerts

## 🖥️ Output
### Output 1 – Normal Student Detection

Student detected with cyan bounding box

Status displayed as Normal

### Output 2 – Cheating Detection Alert

Sustained suspicious behavior detected

Bounding box turns red

Evidence image saved automatically

Note: Detection accuracy depends on camera angle, lighting conditions, and threshold configuration.

## 📊 Results and Impact

The proposed system successfully identifies examinees and monitors their behavior in real time. By incorporating temporal analysis, the system significantly reduces false cheating alerts caused by momentary movements. Automated evidence logging ensures transparency and provides reliable records for post-exam review.

This project demonstrates how AI-based monitoring systems can enhance examination integrity while reducing dependence on manual invigilation.

## 🚀 Future Enhancements

Face recognition for identity verification

Eye-gaze tracking for improved behavior analysis

Mobile phone and object detection

Multi-student tracking with unique IDs

Web-based dashboard for examiners

Cloud-based storage for logs and evidence

## 📚 Articles Published / References

J. Redmon et al., “You Only Look Once: Unified, Real-Time Object Detection,” CVPR, 2016.

Ultralytics, “YOLOv8 Documentation,” 2023.

Szeliski, R., Computer Vision: Algorithms and Applications, Springer.

OpenCV Documentation – https://opencv.org
