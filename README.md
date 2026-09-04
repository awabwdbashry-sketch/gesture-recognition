# Gesture Recognition ✋🤖

A real-time hand gesture recognition project using computer vision and hand landmark detection.

The application uses **MediaPipe Hands** to detect hand landmarks and analyzes finger positions and distances to recognize different hand gestures.

## ✨ Features

- Real-time hand tracking
- Hand gesture recognition
- Finger-state analysis
- Detects multiple common gestures
- Live webcam visualization
- Supports gestures such as:
  - Fist
  - Thumbs Up
  - Thumbs Down
  - One Finger
  - Peace
  - Open Hand
  - Five Fingers
  - OK Gesture

## 🛠️ Technologies

- Python
- OpenCV
- MediaPipe
- NumPy
- Math

## ⚙️ How It Works

The webcam captures the user's hand in real time.

MediaPipe Hands detects the hand landmarks.

The application then analyzes:

1. Finger positions.
2. Finger states.
3. Relative landmark positions.
4. Distance between the thumb and index finger for the OK gesture.
5. The resulting hand configuration is mapped to a recognized gesture.

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/awabwdbashry-sketch/gesture-recognition.git
cd gesture-recognition