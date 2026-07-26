# Landmark Detection System

A real-time **Landmark Detection System** built using **Python**, **OpenCV**, and **Google MediaPipe**. This project detects and visualizes **facial landmarks**, **body pose landmarks**, and **hand landmarks** from images or video streams, making it suitable for computer vision, human-computer interaction, gesture recognition, fitness tracking, and augmented reality applications.

---

## 📖 Overview

The system uses Google's **MediaPipe** framework to perform high-speed landmark detection with pre-trained machine learning models. It can detect:

- 👤 **Face Mesh** – 468 facial landmarks
- 🧍 **Pose Estimation** – 33 body landmarks
- ✋ **Hand Tracking** – 21 landmarks per detected hand

The notebook demonstrates how to initialize MediaPipe models, process images, and draw landmarks with OpenCV.

---

## ✨ Features

- Real-time landmark detection
- Face Mesh detection (468 landmarks)
- Full body pose estimation (33 landmarks)
- Hand landmark detection (21 landmarks per hand)
- Supports multiple detected faces and hands
- Visualizes landmarks with MediaPipe drawing utilities
- Modular helper functions for easy extension

---

## 🛠️ Technologies Used

- Python 3.x
- OpenCV
- MediaPipe
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Project Structure

```
landmark-detection-system/
│
├── landmark_detection_system.ipynb
├── README.md
├── requirements.txt
├── images/
├── outputs/
└── assets/
```

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/landmark-detection-system.git
```

### 2. Navigate to the Project Folder

```bash
cd landmark-detection-system
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install mediapipe opencv-python matplotlib numpy
```

---

## ▶️ Usage

Open the notebook:

```bash
jupyter notebook landmark_detection_system.ipynb
```

Run all cells sequentially.

The notebook will:

1. Initialize MediaPipe models.
2. Load an image.
3. Detect facial, pose, and hand landmarks.
4. Draw landmarks on the image.
5. Display the final output.

---

## 🧠 Landmark Models

| Model | Number of Landmarks |
|--------|--------------------:|
| Face Mesh | 468 |
| Pose | 33 |
| Hands | 21 per hand |

---

## 📸 Example Output

The system detects:

- Facial mesh with detailed landmark connections
- Human pose skeleton
- Hand keypoints and finger joints

Output images display all detected landmarks with coloured connections for easy visualisation.

---

## 💡 Applications

- Gesture Recognition
- Human Pose Estimation
- Face Tracking
- Virtual Try-On
- Fitness Monitoring
- Sign Language Recognition
- AR/VR Applications
- Driver Monitoring Systems
- Medical Motion Analysis

---

## 📈 Future Improvements

- Real-time webcam support
- Video file processing
- Gesture classification using machine learning
- Face recognition integration
- Emotion detection
- Hand gesture recognition
- Performance optimisation with GPU acceleration
- Streamlit or Flask web application

---

## 📦 Requirements

```
Python >= 3.9
mediapipe
opencv-python
numpy
matplotlib
jupyter
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Anuj Biswal**

B.Tech in Artificial Intelligence & Machine Learning

Interested in:

- Computer Vision
- Deep Learning
- Artificial Intelligence
- Machine Learning
- Human Pose Estimation
- Real-Time Vision Systems

---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub. It helps others discover the project and supports future development.