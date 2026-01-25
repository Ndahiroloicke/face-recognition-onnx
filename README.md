# 🎯 Face Recognition System

> **ArcFace ONNX with 5-Point Facial Landmark Alignment**

A high-performance, modular face recognition system designed for CPU environments. Built with ArcFace ONNX models and advanced facial landmark detection for accurate face alignment and recognition.

---

## ✨ Features

- **ArcFace ONNX Model**: State-of-the-art face recognition using ONNX runtime
- **5-Point Facial Alignment**: Precise face alignment using facial landmarks
- **CPU-Optimized**: Runs efficiently on laptops and desktops without GPU requirements
- **Modular Architecture**: Clean, well-organized codebase with descriptive naming
- **Educational Focus**: Perfect for learning and practical applications

---

## 🚀 Quick Start

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Installation

1. **Install Dependencies**
   ```bash
   pip install opencv-python numpy onnxruntime scipy tqdm mediapipe
   ```

2. **Initialize Project**
   ```bash
   python init_project.py
   ```

---

## 📖 Usage Guide

### Enroll Faces

Enroll new faces into the recognition system:

```bash
python -m src.enroll
```

### Recognize Faces

Run face recognition on images or video:

```bash
python -m src.recognize
```

### Testing Modules

Test individual components:

```bash
# Camera module
python -m src.camera

# Detection module
python -m src.detect
```

---

## 📁 Project Structure

```
face-recognition-onnx/
├── models/          # ONNX model files
├── src/            # Source code modules
├── init_project.py # Project initialization script
└── requirements.txt # Python dependencies
```

---

## 🔧 Technical Details

- **Face Detection**: MediaPipe-based face detection
- **Face Alignment**: 5-point facial landmark alignment
- **Recognition Model**: ArcFace ONNX (optimized for CPU)
- **Image Processing**: OpenCV and NumPy

---

## 📝 License

This project is intended for **educational and non-commercial use**. Feel free to explore, learn, and adapt the code for your learning purposes.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! This is an educational project designed to help others learn about face recognition systems.

---

**Built with ❤️ for education and practical applications**
