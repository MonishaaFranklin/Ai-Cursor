# 🚀 GestureMouse AI

A real-time hand gesture recognition system that lets you control your computer mouse using just your webcam — no extra hardware needed!

![demo-gif](link-to-your-demo.gif)

---

## ✨ Features

✅ Smooth, accurate cursor control  
✅ Pinch thumb + index → left-click  
✅ Pinch thumb + middle → right-click  
✅ Fist gesture → scroll up  
✅ Built entirely with Python & open-source libraries  
✅ Fully offline – works without internet

---

## 🛠️ Built With

- [MediaPipe](https://developers.google.com/mediapipe) – hand tracking
- [OpenCV](https://opencv.org/) – video processing
- [PyAutoGUI](https://pyautogui.readthedocs.io/) – controlling the mouse
- NumPy & math – gesture logic

---

## 📦 Installation

```bash
# Clone this repo
git clone https://github.com/MonishaaFranklin/gesturemouse-ai.git
cd gesturemouse-ai

# Create a virtual environment (recommended)
python -m venv venv
venv\Scripts\activate  # On Windows

# Install required libraries
pip install -r requirements.txt

# Run the gesture mouse
python gesture_mouse.py
