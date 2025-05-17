# 🎮 AI-Powered Gesture-Based Subway Surfer Controller for Hand-Disabled Players


## 📜 Project Description

This project is a **gesture-based AI controller** built using **OpenCV**, **MediaPipe**, and **PyAutoGUI** that allows **individuals with hand disabilities** to play **Subway Surfer** (or similar online games) using only **head movements** detected through a webcam.

The controller **splits the camera frame into four zones**:
- Move head **right** ➡️ Triggers **Right Arrow** key
- Move head **left** ⬅️ Triggers **Left Arrow** key
- Move head **up** ⬆️ Triggers **Up Arrow** key (Jump)
- Move head **down** ⬇️ Triggers **Down Arrow** key (Slide)

This system provides a **hands-free, inclusive gaming experience** without any external hardware — just a normal webcam!


## ✨ Features

- 🎥 Real-time head tracking using MediaPipe.
- 🖥️ Screen split into four virtual control zones.
- 🕹️ Automated keyboard keypress simulation.
- ⚡ Lightweight and fast performance.
- ♿ Specially designed for hand-disabled individuals.
- 🚀 Easy to set up and run.


## 📦 Technologies Used

- Python 3.x
- OpenCV (cv2)
- MediaPipe
- PyAutoGUI


## 🛠️ Setup Instructions

```bash
git clone https://github.com/Abhishek2634/subway_surfer_head_control.git
cd subway_surfer_head_control
```

## Create and Activate a Virtual Environment (Python 3.10 Recommended)
```bash
python3.10 -m venv venv

# On macOS/Linux:
source venv/bin/activate

# On Windows
venv\Scripts\activate
```

## Install Dependencies
```bash 
pip install opencv-python mediapipe pynput numpy
```

## Run the Application
``` bash 
python main.py
```

