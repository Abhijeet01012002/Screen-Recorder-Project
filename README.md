

# 🎥 Screen Recorder Project 🌀 (Naruto Edition)

[![Python Badge](https://img.shields.io/badge/Language-Python-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A **ninja-level Python screen recorder** that captures your desktop like a shinobi capturing a target 👀. Perfect for tutorials, gameplay, or recording anything on your screen. Beginner-friendly project to learn **Python GUI, screen capture, and video processing**.

![Naruto Banner]([[https://upload.wikimedia.org/wikipedia/en/9/94/Naruto_Uzumaki.png](https://share.google/images/EaVd8CjuGBfdUrtgo)](https://images.wallpapersden.com/image/download/naruto-pain-minimal_bGppbWyUmZqaraWkpJRnZ2ZtrWZnaWw.jpg))

---

## ✨ Key Features 🥷

* 🖥️ **Full Screen Capture:** Record everything happening on your desktop like a true ninja spying mission.
* ⏱️ **Custom FPS:** Set frames per second for smooth recordings.
* 💾 **Save as Video:** Automatically saves recordings as MP4 files.
* 🎮 **Versatile Use:** Record tutorials, gameplay, meetings, or anything.
* ✅ **Easy to Use:** Lightweight Python script, no complex setup.

---

## 💻 Technologies Used ⚡

* **Python 3** – Core programming language
* **pyautogui** – Screen capture like a ninja eye technique
* **OpenCV (cv2)** – Frame processing and video saving
* **numpy** – Handles arrays for video frames

---

## 🚀 Getting Started 🪄

### Prerequisites

Install Python 3 and required libraries:

```bash
pip install pyautogui opencv-python numpy
```

### Installation & Running

1. **Clone the Repository**

```bash
git clone https://github.com/Abhijeet07012002/Screen-Recorder-Project.git
```

2. **Go to Project Folder**

```bash
cd Screen-Recorder-Project
```

3. **Run the Script**

```bash
python screenRecorder.py
# Or python3 screenRecorder.py
```

4. **Stop Recording**
   Press `Ctrl + C` and the video will be saved automatically.

---

## 🕹️ How to Use 🥷

1. Run the script
2. Recording starts automatically
3. Record your screen while you train like a ninja
4. Press `Ctrl + C` to stop and save

---

## 📸 Sample Code Snippet 💻

```python
import pyautogui
import cv2
import numpy as np

screen_size = pyautogui.size()
fourcc = cv2.VideoWriter_fourcc(*"XVID")
out = cv2.VideoWriter("recording.mp4", fourcc, 20.0, screen_size)

while True:
    img = pyautogui.screenshot()
    frame = np.array(img)
    frame = cv2.cvtColor(frame, cv2.COLOR_BGR2RGB)
    out.write(frame)
```

---

## ✍️ Author 🌸


* **Abhijeet** - [GitHub Profile](https://github.com/Abhijeet01012002)
* **Abhijeet** - [Linkdin Profile](https://www.linkedin.com/in/abhijeet-bhagat-4912b2382)
* **Abhijeet** - [Abhijeet.akj@gmail.com](abhijeet.akj@gmail.com)
* **Abhijeet** - [Instagram Profile](https://www.instagram.com/abhijeet.official.30/)

---


