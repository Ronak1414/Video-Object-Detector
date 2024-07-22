# Video-Object-Detector
VideoObjectDetector is a Python-based tool designed for extracting and saving objects from video frames. It utilizes OpenCV's pre-trained MobileNet SSD model to detect objects within each frame of a video file. This repository provides a comprehensive solution for:

Reading Frames: Efficiently processing each frame from a video of arbitrary length.
Object Detection: Leveraging MobileNet SSD to detect objects within frames with high accuracy.
Cropping and Saving: Automatically cropping detected objects and saving them as individual images in a specified directory.
Features:

Batch Processing: Handles long videos, processing each frame sequentially.
High Accuracy: Utilizes a state-of-the-art pre-trained model for accurate object detection.
Customizable: Easily configurable for different video files and output settings.
User-Friendly: Simple interface for setting up video input and output directories.


Requirements:
Python 3.x
OpenCV
NumPy


Installation:
To install the required libraries, run:
pip install opencv-python opencv-python-headless numpy
Usage:




Place the deploy.prototxt and mobilenet_iter_73000.caffemodel files in the same directory as the script.
Update the video_path variable with the path to your video file.
Run the script to process the video and save cropped objects to the specified output folder.
Example:
video_path = 'your_video.mp4'
output_path = 'cropped_objects'
main(video_path, output_path)
