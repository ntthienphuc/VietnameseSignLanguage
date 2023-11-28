
# Real-Time Hand Gesture Recognition

## Overview
This project is focused on developing a real-time hand gesture recognition system using computer vision and machine learning techniques. The core technology involves the use of OpenCV, Mediapipe, and TensorFlow to detect hand gestures and interpret them into predefined actions or commands.

## Prerequisites
Before running this project, ensure you have the following installed:
- Python 3.8 or later
- OpenCV
- Mediapipe
- NumPy
- Matplotlib
- TensorFlow

## Installation
Clone the repository to your local machine:
```
git clone [repository URL]
```

Install the required packages:
```
pip install opencv-python
pip install mediapipe
pip install numpy
pip install matplotlib
pip install tensorflow
```

## Usage
The project consists of two main parts: Data Collection and Inference.

### Data Collection
This module is responsible for collecting hand gesture data to train the machine learning model. It captures hand landmarks using a webcam and stores the data in a specified format.

To run the data collection script:
```
python collect_data.py
```

### Inference
This module uses the trained model to predict hand gestures in real-time. It captures video from a webcam and utilizes the model to interpret the hand gestures.

To run the inference script:
```
python infer.py
```

## Contributing
Contributions to this project are welcome. Please ensure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
