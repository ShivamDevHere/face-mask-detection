# 😷 Face Mask Detection

<p align="center">
  <b>Real-Time Mask Detection Using Deep Learning & Computer Vision</b>
</p>

<p align="center">
  Detect whether a person is wearing a face mask using a trained deep learning model and live camera input.
</p>

<p align="center">
  <a href="YOUR_LIVE_DEMO_URL">🚀 Live Demo</a> •
  <a href="https://github.com/ShivamDevHere">👨‍💻 My GitHub</a> •
  <a href="https://github.com/ShivamDevHere/deep-learning">🧠 Deep Learning Projects</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Deep%20Learning-CNN-orange?style=for-the-badge" alt="Deep Learning"/>
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <!-- <img src="https://img.shields.io/badge/Task-Supervised%20Learning-blue?style=for-the-badge" alt="Supervised Learning"/> -->
</p>

---

## 📌 About the Project

**Face Mask Detection** is a computer vision project that uses a Convolutional Neural Network (CNN) to classify faces into two categories:

- 😷 **With Mask**
- 🙂 **Without Mask**

The model is trained on labeled images and integrated with OpenCV to process live webcam frames and display the predicted class directly on the video.

## ✨ Key Features

- 🧠 **CNN Classification** — Learns mask-related visual patterns from images.
- 📷 **Live Webcam Detection** — Processes real-time camera frames.
- 🏷️ **Instant Predictions** — Displays mask status on the video.
- 👥 **Face Detection** — Identifies face regions for classification.
- ⚡ **Real-Time Processing** — Continuously analyzes incoming frames.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming |
| TensorFlow / Keras | Model training and inference |
| OpenCV | Webcam access and image processing |
| NumPy | Numerical operations |
| CNN | Mask classification |

## ⚙️ How It Works

```text
Labeled Image Dataset
        ↓
Image Preprocessing
        ↓
CNN Model Training
        ↓
Trained Model
        ↓
Live Webcam Feed
        ↓
Face Detection & Classification
        ↓
With Mask / Without Mask
        ↓
Display Prediction on Video
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ShivamDevHere/face-mask-detection.git
cd face-mask-detection
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Project

After training the model and configuring the model path, run the detection script:

```bash
python src/detect.py
```

> **Note:** Update the commands and file paths to match the final project structure.

## 📂 Project Structure

```text
face-mask-detection/
├── dataset/
│   ├── with_mask/
│   └── without_mask/
├── notebooks/
│   └── model_training.ipynb
├── models/
├── src/
│   ├── train.py
│   └── detect.py
├── requirements.txt
└── README.md
```

## 🌐 Project Links

- 🚀 **Live Demo:** [Try Face Mask Detection](YOUR_LIVE_DEMO_URL)
- 💻 **Source Code:** [GitHub Repository](https://github.com/ShivamDevHere/face-mask-detection)
- 🧠 **Parent Repository:** [Deep Learning Projects](https://github.com/ShivamDevHere/deep-learning)

<!-- ## 🔗 Similar Projects

Explore these projects for implementation ideas and comparisons.

| Project | GitHub Repository | Live Demo |
|---|---|---| -->
<!-- | Face Mask Detector | [View Source](https://github.com/Karan-Malik/FaceMaskDetector) | [View Demo](https://github.com/Karan-Malik/FaceMaskDetector) | -->
<!-- | Face Mask Detection & Alert System | [View Source](https://github.com/sidharth178/Face-Mask-Detection-and-Alert-System) | [View Demo](https://sidharth178.github.io/Face-Mask-Detection-and-Alert-System/) | -->
<!-- | Streamlit Face Mask Detection | [View Source](https://github.com/techyhoney/Facemask_Detection) | [Open Web App](https://share.streamlit.io/techyhoney/facemask_detection/deploy.py) | -->

## 👨‍💻 Author

**Shivam Srivastava**

- GitHub: [@ShivamDevHere](https://github.com/ShivamDevHere)
- LinkedIn: [Connect with me](https://linkedin.com/in/shivamdevhere)
- Portfolio: [Visit My Portfolio](https://portfolio-ruby-one-66.vercel.app/)

---

<p align="center">
  ⭐ If you find this project useful, consider giving it a star!
</p>
