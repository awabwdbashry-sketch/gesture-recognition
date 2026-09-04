# ✋ Gesture Recognition

A real-time computer vision project that recognizes different hand gestures using a webcam.

The project uses **MediaPipe** to detect hand landmarks and **OpenCV** to process the live camera feed. By analyzing the positions of the detected landmarks, the application identifies predefined hand gestures such as **Fist, Thumbs Up, Thumbs Down, One Finger, Peace, Open Hand, and OK**.

## ✨ Features

- ✋ Real-time hand tracking
- 🤖 Real-time gesture recognition
- 🎥 Webcam-based detection
- 🧠 Landmark-based gesture classification
- 👊 Fist gesture detection
- 👍 Thumbs Up detection
- 👎 Thumbs Down detection
- ☝️ One Finger detection
- ✌️ Peace gesture detection
- 🖐️ Open Hand detection
- 👌 OK gesture detection
- ⚡ Fast real-time processing
- 📊 Displays the recognized gesture on the screen

## 🛠️ Technologies Used

- 🐍 Python
- 👁️ OpenCV
- ✋ MediaPipe

## ⚙️ How It Works

The application captures video from the webcam using OpenCV.

MediaPipe detects the user's hand and generates a collection of landmarks representing the hand structure.

The program analyzes the relationships between these landmarks to determine the position and state of the fingers.

Based on these finger positions, the application compares the detected hand configuration with predefined gesture patterns.

When a matching pattern is detected, the corresponding gesture name is displayed on the screen.

## 🔄 Processing Pipeline

```text
Webcam
   ↓
OpenCV
   ↓
MediaPipe Hand Detection
   ↓
Hand Landmark Detection
   ↓
Finger Position Analysis
   ↓
Gesture Classification
   ↓
Display Gesture
```

## 🤖 Supported Gestures

| Gesture | Meaning |
|---|---|
| 👊 FIST | Closed hand |
| 👍 THUMBS UP | Positive gesture |
| 👎 THUMBS DOWN | Negative gesture |
| ☝️ ONE | One raised finger |
| ✌️ PEACE | Two raised fingers |
| 🖐️ OPEN HAND / FIVE | Five raised fingers |
| 👌 OK | OK gesture |

## 🧠 Gesture Recognition Logic

The recognition system is based on the relative positions of the hand landmarks.

The application examines which fingers are extended or folded and analyzes the configuration of important hand points.

Different combinations of finger states correspond to different gestures.

This approach provides a simple and practical way to build a gesture recognition system without requiring a separate machine-learning training process for every gesture.

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/awabwdbashry-sketch/gesture-recognition.git
cd gesture-recognition
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment on Windows:

```bash
venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## 📋 Requirements

- 🐍 Python 3.9 or newer
- 📷 Webcam
- 💻 Windows, Linux, or macOS

### Python Dependencies

```text
opencv-python
mediapipe
```

## ▶️ Usage

Run the main application:

```bash
python gesture_ai.py
```

Place your hand in front of the webcam.

The application will detect the hand, analyze its landmarks, and display the recognized gesture in real time.

Try different supported gestures such as:

- 👊 Fist
- 👍 Thumbs Up
- 👎 Thumbs Down
- ☝️ One
- ✌️ Peace
- 🖐️ Open Hand
- 👌 OK

## 📁 Project Structure

```text
gesture-recognition/
│
├── gesture_ai.py
├── requirements.txt
├── README.md
├── README_AR.md
└── .gitignore
```

## 💡 Applications

Gesture recognition can be used as a foundation for many interactive systems.

Possible applications include:

- 🖥️ Touchless computer interfaces
- 🎮 Gesture-controlled games
- 🤖 Robot control
- ♿ Accessibility systems
- 🏠 Smart home control
- 🎓 Computer vision education
- 🧪 Human-computer interaction experiments
- 📱 Touchless mobile interfaces

## ⭐ Advantages

- Simple gesture recognition approach
- Real-time performance
- Uses a standard webcam
- No special hardware required
- Easy to understand and extend
- Demonstrates practical hand landmark analysis
- Supports multiple predefined gestures

## 🚀 Future Improvements

Possible improvements include:

- 🧠 More advanced gesture classification
- ✋ Support for additional gestures
- 👐 Multi-hand gesture recognition
- 🎯 Improved detection accuracy
- 📊 Gesture confidence scores
- ⚙️ Custom gesture configuration
- 🤖 Integration with robots and smart devices
- 🎮 Integration with games and applications

## 🎯 Project Purpose

The main goal of this project is to demonstrate how **hand landmarks and finger positions** can be used to recognize predefined hand gestures in real time.

It provides a practical introduction to gesture-based interaction using **Python, OpenCV, and MediaPipe**.

## 📄 License

This project is available for educational and personal use.

---

⭐ If you find this project useful, consider giving the repository a star!

**GitHub:** `https://github.com/awabwdbashry-sketch/gesture-recognition`