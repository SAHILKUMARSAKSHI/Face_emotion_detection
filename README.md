# Facial Emotion Recognition using OpenCV & DeepFace

This project performs real-time facial emotion detection using the system webcam.  
It uses **OpenCV** for video processing and **DeepFace** for deep learning-based emotion recognition.

---

## Features
- Real-time webcam capture  
- Emotion prediction using DeepFace  
- Face detection using RetinaFace  
- Supports emotions: happy, sad, angry, fear, surprise, disgust, neutral  
- Lightweight and easy to extend  

---

## Project Structure

Facial-Emotion-Recognition/
│── emotion.py
│── README.md
│── requirements.txt
└── screenshots/ (optional)


---

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/SAHILKUMARSAKSHI/Facial-Emotion-Recognition.git
cd Facial-Emotion-Recognition

2. (Optional) Create virtual environment
conda create -n fer python=3.10 -y
conda activate fer

3. Install dependencies
pip install -r requirements.txt

If you don't have a requirements file, install manually:
pip install opencv-python deepface retinaface tensorflow==2.11.0 tf-keras numpy

Running the project
python emotion.py


Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

