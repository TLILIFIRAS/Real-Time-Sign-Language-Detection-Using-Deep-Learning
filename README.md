# Real-Time-Sign-Language-Detection-Using-Deep-Learning
This project demonstrates a Sign Language Detection system that utilizes Action Recognition with an LSTM (Long Short-Term Memory) Deep Learning model. The system leverages MediaPipe's Holistic Keypoints to extract skeletal data from video sequences, which is then used to predict sign language gestures.

## Requirements

To run this project, you need the following dependencies:

- Python (3.6 or higher)
- OpenCV (cv2)
- NumPy
- Matplotlib
- Tensorflow
- Keras
- Mediapipe

You can install the required libraries using pip:

```bash
pip install opencv-python numpy matplotlib tensorflow keras mediapipe
```
## How it works

The Sign Language Detection system follows these steps:

1. **Extract MediaPipe Holistic Keypoints:** The system uses the mediapipe library to extract facial, pose, left hand, and right hand keypoints from video frames. These keypoints represent the sign language gestures.

2. **Build a Sign Language Model:** The extracted keypoints are fed into a deep neural network with LSTM layers. This model handles the sequence of keypoints, enabling effective detection of sign language actions.

3. **Real-time Sign Language Prediction:** The trained model predicts sign language gestures in real-time using video sequences. The application captures the camera feed, processes each frame, and displays the detected action label on the screen.

## Running the Code

### Clone the repository:
```bash
git clone https://github.com/TLILIFIRAS/Real-Time-Sign-Language-Detection-Using-Deep-Learning.git
cd sign-language-detection
```
