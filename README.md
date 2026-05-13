# 🚗 Car Object Detection using YOLOv8 & Computer Vision

A Computer Vision project for detecting cars in images and videos using **YOLOv8**, Deep Learning, and Object Detection techniques.

This project demonstrates the use of Python, OpenCV, and Machine Learning models for real-time vehicle detection and visualization.

---

## 📌 Project Overview

The objective of this project is to build an intelligent vehicle detection system capable of identifying cars from images and video streams using modern Computer Vision and Deep Learning algorithms.

The notebook includes:
- Data preprocessing
- Dataset preparation for YOLO format
- Image analysis
- Vehicle detection
- YOLOv8 model training
- Visualization of predictions
- Object detection workflow

---

## 📌 Features

- 🚘 Car detection in images
- 🎥 Vehicle detection in video streams
- 🧠 YOLOv8 Deep Learning implementation
- 📊 Visualization of detection results
- 📦 Jupyter Notebook implementation
- ⚡ Easy to run and modify
- 📁 Automatic dataset preparation
- 🏷️ Bounding box annotation generation

---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- YOLOv8 (Ultralytics)
- Jupyter Notebook

Optional:
- TensorFlow
- PyTorch
- Haar Cascades

---

## 📂 Dataset

The dataset used in this project is available on Kaggle:

🔗 Dataset Link:  
https://www.kaggle.com/datasets/sshikamaru/car-object-detection

The dataset contains:
- Car images
- Bounding box annotations
- Training and testing samples

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Ghizlane8/Car-object-detection.git
```

Go to the project folder:

```bash
cd Car-object-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Install YOLOv8:

```bash
pip install ultralytics
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## ▶️ Usage

Open the notebook:

```bash
tp-car-object-detection.ipynb
```

Run all cells to:
- Load the dataset
- Prepare YOLO annotations
- Split training and validation data
- Train the YOLOv8 model
- Detect cars
- Visualize predictions

---

## 🧠 YOLOv8 Training

The project uses the **YOLOv8m** model from Ultralytics.

Example training configuration:

```python
model = YOLO('yolov8m.pt')
model.train(data='dataset.yaml', epochs=5, batch=32)
```

Dataset configuration:

```yaml
path: ./cars
train: images/train
val: images/valid

nc: 1
names: ['car']
```

---

## 📸 Results

The model successfully detects vehicles and generates bounding boxes around detected cars.

### Example Result

<img width="708" height="401" alt="image" src="https://github.com/user-attachments/assets/a1b3be5d-ac77-4110-b0b6-f20ea7ded04d" />

---

## 📊 Workflow

1. Dataset Loading
2. Data Cleaning & Processing
3. Train/Validation Split
4. YOLO Annotation Generation
5. Dataset Configuration
6. YOLOv8 Model Training
7. Vehicle Detection
8. Prediction Visualization
9. Performance Evaluation

---

## 🧠 Concepts Used

- Computer Vision
- Object Detection
- Deep Learning
- YOLOv8
- Image Processing
- Bounding Boxes
- Feature Extraction
- Data Preprocessing

---

## 📈 Future Improvements

- Real-time webcam detection
- Traffic monitoring system
- Speed estimation
- Multi-object tracking
- Web application deployment
- YOLOv9 integration
- Model optimization for edge devices

---

## 📚 Learning Objectives

This project was developed to practice:
- Machine Learning fundamentals
- Deep Learning workflows
- Computer Vision techniques
- YOLO object detection
- Python for AI applications
- Dataset preprocessing and annotation

---

## 🤝 Contributing

Contributions are welcome.

Feel free to:
- Fork the repository
- Improve the project
- Add new features
- Submit pull requests

---

## 🌐 Connect With Me

<p align="left">
  <a href="https://github.com/Ghizlane8" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Ghizlane8-181717?style=for-the-badge&logo=github" />
  </a>

  <a href="https://www.linkedin.com/in/ghizlane-baali-a42505267/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Ghizlane%20Baali-0A66C2?style=for-the-badge&logo=linkedin" />
  </a>

  <a href="mailto:baali.ghizlane2@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 👩‍💻 About the Author

**Ghizlane Baali**  
Data Scientist | Data Analyst & AI Enthusiast

Passionate about Artificial Intelligence, Machine Learning, Computer Vision, and Data Analytics.

Currently focused on building intelligent systems using Python, OpenCV, YOLOv8, Deep Learning, and predictive modeling techniques.

This project reflects my interest in applying AI technologies to real-world problems through practical and scalable solutions.

---

## ⭐ Support

If you like this project, give it a star ⭐ on GitHub.
