# Computer Vision & Machine Learning Projects

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)](https://www.python.org/downloads/)

A comprehensive collection of Computer Vision and Machine Learning projects showcasing real-world implementations of various CV and ML techniques.

## 📋 Table of Contents

- [About](#about)
- [Projects](#projects)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 About

This repository consolidates multiple Computer Vision and Machine Learning projects developed to demonstrate practical applications of CV/ML algorithms. Each project focuses on specific aspects of computer vision, from facial landmark detection to speech recognition.

## 🚀 Projects

### 1. Eye Blink Detection
**Description:** Real-time eye blink detection using OpenCV and dlib for facial landmark detection.

**Key Features:**
- Real-time detection using webcam
- Facial landmark detection with dlib
- Eye Aspect Ratio (EAR) calculation
- Blink counting mechanism

**Technologies:** Python, OpenCV, dlib, NumPy

**Applications:** Driver drowsiness detection, accessibility tools, human-computer interaction

---

### 2. Eye Movement Detection
**Description:** Eye movement tracking using gaze detection and OpenCV for analyzing eye positions and movements.

**Key Features:**
- Gaze tracking functionality
- Real-time eye position detection
- Movement pattern analysis
- Direction detection (left, right, up, down)

**Technologies:** Python, OpenCV, MediaPipe, NumPy

**Applications:** Accessibility devices, UI/UX research, gaming controls

---

### 3. Face Recognition
**Description:** Face recognition and person detection in video streams using deep learning techniques.

**Key Features:**
- Face detection and recognition
- Multiple face tracking
- Person identification in video
- Real-time processing

**Technologies:** Python, OpenCV, Deep Learning, face_recognition library

**Applications:** Security systems, attendance tracking, photo organization

---

### 4. Shoulder Movement Detection
**Description:** Shoulder movement detection using MediaPipe pose estimation for tracking body posture and movements.

**Key Features:**
- Pose estimation using MediaPipe
- Shoulder joint tracking
- Movement angle calculation
- Exercise form analysis

**Technologies:** Python, OpenCV, MediaPipe, NumPy

**Applications:** Fitness tracking, physical therapy, posture correction

---

### 5. Video Transcription
**Description:** Automated video transcription converting audio to text using speech recognition technology.

**Key Features:**
- Audio extraction from video
- Speech-to-text conversion
- Multiple language support
- Timestamp generation

**Technologies:** Python, speech_recognition, pydub, MoviePy

**Applications:** Subtitle generation, content accessibility, meeting transcription

---

## 🛠️ Technologies Used

- **Programming Language:** Python 3.7+
- **Computer Vision:** OpenCV, dlib
- **Machine Learning:** MediaPipe, TensorFlow
- **Deep Learning:** Face Recognition, CNN
- **Audio Processing:** speech_recognition, pydub
- **Data Processing:** NumPy, Pandas
- **Development Environment:** Jupyter Notebook

## 📦 Installation

### Prerequisites
```bash
python --version  # Python 3.7 or higher required
```

### Clone the Repository
```bash
git clone https://github.com/divyanshdubey/Computer-Vision-ML-Projects.git
cd Computer-Vision-ML-Projects
```

### Install Dependencies
```bash
pip install opencv-python
pip install dlib
pip install mediapipe
pip install face-recognition
pip install speech-recognition
pip install pydub
pip install numpy
pip install pandas
```

Or install all at once:
```bash
pip install opencv-python dlib mediapipe face-recognition speech-recognition pydub numpy pandas
```

## 💻 Usage

Each project is contained in its own directory with detailed instructions. Navigate to the specific project folder and follow the README or notebook instructions.

### General Usage Pattern:
```python
# Import required libraries
import cv2
import numpy as np

# Initialize camera/video source
cap = cv2.VideoCapture(0)

# Process frames and apply algorithms
# (Specific implementation varies by project)

# Release resources
cap.release()
cv2.destroyAllWindows()
```

## 📁 Project Structure

```
Computer-Vision-ML-Projects/
│
├── Eye-Blink-Detection/
│   ├── notebooks/
│   ├── models/
│   └── README.md
│
├── Eye-Movement-Detection/
│   ├── notebooks/
│   ├── scripts/
│   └── README.md
│
├── Face-Recognition/
│   ├── notebooks/
│   ├── sample_images/
│   └── README.md
│
├── Shoulder-Movement-Detection/
│   ├── notebooks/
│   └── README.md
│
├── Video-Transcription/
│   ├── notebooks/
│   ├── sample_videos/
│   └── README.md
│
├── .gitignore
├── LICENSE
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

**Divyansh Dubey**
- GitHub: [@divyanshdubey](https://github.com/divyanshdubey)
- Email: vaarun.dub123@gmail.com
- LinkedIn: [Connect with me](https://www.linkedin.com/in/divyanshdubey/)
 Portfolio: [Visit my portfolio](https://bit.ly/divyanshdubey)

## 🙏 Acknowledgments

- OpenCV community for excellent documentation
- dlib library for facial landmark detection
- MediaPipe team for pose estimation solutions
- Face Recognition library developers
- All open-source contributors

---

⭐ **If you find this repository helpful, please consider giving it a star!**

Made with ❤️ by Divyansh Dubey
