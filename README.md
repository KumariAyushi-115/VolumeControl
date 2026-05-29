# 🖐️ Gesture Volume Control

A lightweight, high-impact Python script that utilizes computer vision to control your system's volume using real-time hand gestures. Built in just **50 lines of code**, this project showcases an efficient integration of hand-tracking landmarks with automation utilities.

---

## ⚡ How It Works

The application captures video input from your webcam, detects hand landmarks, and maps the physical distance between your **thumb** and **index finger** directly to your computer's master volume controls.

* **Increase Volume:** Move your thumb and index finger further apart.
* **Decrease Volume:** Pinch your thumb and index finger closer together.

---

## 🚀 Tech Stack & Core Libraries

* **Python** (Core Scripting)
* **OpenCV (`cv2`)**: Handles webcam video capture, frame processing, and UI rendering.
* **MediaPipe (`mediapipe`)**: Provides the underlying machine learning pipeline for ultra-fast, real-time hand skeleton tracking.
* **PyAutoGUI (`pyautogui`)**: Simulates native keyboard volume hotkeys (`volumeup`, `volumedown`) to interact with the host OS.

---

## 🛠️ Getting Started

### Prerequisites

Ensure you have Python installed, then install the required dependencies via `pip`:

```bash
pip install opencv-python mediapipe pyautogui
