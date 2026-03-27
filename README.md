# Smart Gallery Application

An AI-powered photo management system built using Django and Python that automatically organizes images using face recognition, clustering, and intelligent processing techniques.

---

## Features

- Face Recognition  
  Detects faces using InsightFace and extracts embeddings for each detected face  

- Automatic Person Grouping  
  Groups similar faces using DBSCAN clustering to organize people across photos  

- Smart Event Detection  
  Groups photos into events based on time gaps and assigns contextual labels  

- AI-Based Image Processing  
  Performs smart cropping focusing on faces and generates collages  

- Image Search  
  Allows searching photos by uploading a face image using similarity matching  

---

## Tech Stack

- Backend: Django, Python  
- AI/ML: InsightFace, Scikit-learn  
- Image Processing: OpenCV, PIL  
- Database: SQLite  

---

## Project Structure
smart-gallery-application/
│── core/
│── gallery/
│── templates/
│── manage.py
│── requirements.txt
│── README.md


---

## Installation and Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/smart-gallery-application.git
cd smart-gallery-application
