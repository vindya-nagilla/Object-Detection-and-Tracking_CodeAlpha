# Object-Detection-and-Tracking_CodeAlpha
Developed a real-time Object Detection and Tracking system using YOLOv8 and ByteTrack. The application detects multiple objects in video streams, draws bounding boxes, and assigns unique tracking IDs for continuous monitoring. Implemented using Python, OpenCV, and deep learning techniques to achieve accurate and efficient object tracking.

# 📌 Project Overview

This project implements a real-time Object Detection and Tracking system using YOLOv8 and ByteTrack. The system detects multiple objects in a video, draws bounding boxes around them, and assigns unique tracking IDs to follow each object across frames.

# 🚀 Features
Real-time object detection using YOLOv8.<br>
Multi-object tracking with ByteTrack.<br>
Bounding box visualization with class labels.<br>
Unique tracking IDs for each detected object.<br>
Supports video file input.<br>
Saves processed output video with annotations.<br>
# 🛠️ Technologies Used
Python<br>
OpenCV<br>
YOLOv8 (Ultralytics)<br>
ByteTrack<br>
Google Colab<br>
NumPy<br>
# 📂 Workflow
Load a pre-trained YOLOv8 model.<br>
Read video frames using OpenCV.<br>
Detect objects in each frame.<br>
Apply ByteTrack to track detected objects.<br>
Draw bounding boxes and tracking IDs.<br>
Save the annotated output video.<br>
# 🎯 Applications
Smart Surveillance Systems<br>
Traffic Monitoring and Vehicle Tracking<br>
Crowd Analysis<br>
Security and Safety Monitoring<br>
Autonomous Vehicle Research<br>
# 📊 Output

The output video displays:

Detected object labels<br>
Bounding boxes<br>
Confidence scores<br>
Unique tracking IDs for each object<br>
# 📈 Future Enhancements
Real-time webcam support.<br>
Object counting and analytics.<br>
Speed estimation of moving objects.<br>
Integration with DeepSORT for advanced tracking.<br>
Custom-trained YOLO models for specific use cases.<br>
# 🔗 Repository Structure
Object-Detection-and-Tracking/<br>
│
├── object_tracking.ipynb<br>
├── input_video.mp4<br>
├── tracked_output.mp4<br>
├── requirements.txt<br>
└── README.md
# 📌 Conclusion

This project demonstrates the integration of deep learning-based object detection and tracking techniques to accurately identify and monitor multiple objects in video streams. By combining YOLOv8 with ByteTrack, the system achieves efficient and reliable real-time tracking performance.
