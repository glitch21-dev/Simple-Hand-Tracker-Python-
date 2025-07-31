# 🖐️ Real-Time Hand Tracker (OpenCV + Mediapipe)

This is a simple hand tracking project built using OpenCV and Mediapipe. It captures video from your webcam, detects your hand, tracks finger landmarks, and displays a cropped hand view alongside the full frame.

## 📷 Features

- Real-time hand detection using webcam
- Finger tracking with Mediapipe's landmark model
- Bounding box around detected hand
- Two camera windows:
  - Full frame with visual markers
  - Cropped view focused on the hand

## 🛠️ Requirements

- Python 3.10 (required for Mediapipe compatibility)
- OpenCV
- Mediapipe

## 📦 Installation

> ⚠️ Make sure you're using Python 3.7 to 3.10 — Mediapipe doesn't support newer versions (like 3.11+)

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/hand-tracker-opencv.git
   cd hand-tracker-opencv
