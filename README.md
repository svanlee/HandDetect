# HandDetect
This repository contains a real-time hand detection project using Tensorflow's Object Detection API. It includes training scripts, a hand detection model, and demo scripts for video and webcam input. The model can also be exported for use in Tensorflow.js and Android.

Usage:

To use this script, simply clone the repository and run the main.py script. The script will open a window displaying real-time video from your webcam with hand landmarks overlaid.

Customization:

The handDetector class can be customized by passing different parameters to its constructor. For example, you can increase the maxHands parameter to detect more hands, or decrease the detectionCon parameter to increase the sensitivity of the hand detection algorithm.

Dependencies:

This script requires the following dependencies:

OpenCV
Mediapipe
You can install these dependencies using pip:

Edit
Full Screen
Copy code
pip install opencv-python mediapipe
Contributing:

Contributions to this project are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

License:

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments:

This script was created using the Mediapipe library, which is an open-source framework for building cross-platform multimodal applied machine learning pipelines. Thank you to the Mediapipe team for creating this amazing tool!
