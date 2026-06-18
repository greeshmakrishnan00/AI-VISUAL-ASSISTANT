# AI Visual Assistant

## 📌 Project Overview

AI Visual Assistant Pro is a real-time computer vision application that uses YOLOv8 to detect and recognize objects through a webcam. The system provides voice feedback, displays object names with confidence scores, and automatically saves screenshots of detected objects. It works completely offline, making it a fast and intelligent visual assistance solution.

## 🚀 Features

* Real-time object detection using YOLOv8
* Live webcam-based object recognition
* Voice output for detected objects
* Displays object names and confidence scores
* Automatic screenshot saving of detected objects
* Saves cropped images of detected objects
* Works completely offline
* Lightweight and easy to use

## 🛠️ Technologies Used

* Python
* OpenCV
* YOLOv8 (Ultralytics)
* Pyttsx3 (Text-to-Speech)

## 📂 Project Structure

```text
AI_Visual_Assistant_Pro/
│
├── AI_VISUAL_ASSISTANT.py
├── yolov8n.pt
├── Detected_Objects/
├── requirements.txt
└── README.md
```

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/AI-Visual-Assistant-Pro.git
cd AI-Visual-Assistant-Pro
```

### Install Dependencies

```bash
pip install ultralytics opencv-python pyttsx3
```

### Download YOLOv8 Model

```python
from ultralytics import YOLO
YOLO("yolov8n.pt")
```

## ▶️ Run the Project

```bash
python AI_VISUAL_ASSISTANT.py
```

## 🎯 How It Works

1. Captures live video from the webcam.
2. Detects objects using YOLOv8.
3. Draws bounding boxes and confidence scores.
4. Announces newly detected objects through voice output.
5. Saves cropped screenshots of detected objects.
6. Displays detection results in real time.

## 📸 Output

* Object Name
* Confidence Score
* Voice Announcement
* Saved Object Screenshot

## 🔮 Future Enhancements

* Face Recognition
* OCR Text Reading
* Currency Detection
* Emotion Recognition
* Object Counting
* Multilingual Voice Support
* Detection History Logging
* AI-Powered Scene Description

## 📊 Domain

Artificial Intelligence | Computer Vision | Deep Learning

## Author

Greeshma R Krishnan

---

⭐ If you like this project, consider giving it a star on GitHub!

