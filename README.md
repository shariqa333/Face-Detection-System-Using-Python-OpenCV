# Face Detection System Using Python and OpenCV

## About the Project

This is a simple Python mini-project that detects human faces using a webcam. It uses OpenCV and the Haar Cascade Classifier to find faces and draw green rectangles around them.

I created this project to learn the basics of computer vision and understand how face detection works using Python.

## Technologies Used

- Python
- OpenCV
- Haar Cascade Classifier
- Webcam

## Features

- Detects faces in real time.
- Can detect multiple faces at once.
- Draws a green rectangle around each detected face.
- Simple and easy to use.

## Requirements

- Python 3.12
- A working webcam
- OpenCV library

## How to Run

**1. Clone this repository**

```bash
git clone https://github.com/YOUR-USERNAME/face-detection.git
```

**2. Open the project folder**

```bash
cd face-detection
```

**3. Install OpenCV**

```bash
python -m pip install opencv-python==4.12.0.88
```

**4. Run the program**

```bash
python face_detection.py
```

Make sure your webcam is connected and accessible.

## How It Works

1. The program opens the webcam and captures video.
2. Each frame is converted into grayscale.
3. The Haar Cascade Classifier detects faces in the frame.
4. Green rectangles are drawn around the detected faces.
5. The video is displayed in a window.

Press **`q`** to close the program.

## Project Structure

```text
face-detection/
├── face_detection.py
├── requirements.txt
└── README.md
```
## Working Images
<img width="807" height="657" alt="Proof" src="https://github.com/user-attachments/assets/1a155313-7317-43ad-a86f-fa7b2f58b445" />


## Conclusion

This project helped me understand how to use Python and OpenCV for face detection. It is a beginner-friendly project that demonstrates a basic application of computer vision.
