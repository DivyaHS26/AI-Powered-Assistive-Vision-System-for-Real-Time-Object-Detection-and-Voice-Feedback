# Voice-Enabled-Real-Time-Object-Tracking-Using-Image-Processing

## 🚀 Overview
An intelligent real-time object detection and tracking system that provides both visual and auditory feedback, making it accessible for visually impaired individuals and enhancing situational awareness in various applications.

## Key Features

- 🎯 **Real-Time Object Detection** - Detects 80+ object classes using YOLOv8
- 🗣️ **Voice Feedback** - Natural language voice summaries of detected objects
- 🎥 **Live Webcam Processing** - Real-time video stream processing
- 📊 **Performance Metrics** - FPS counter and object counting
- 💾 **Screenshot Capture** - Save detection results instantly
- 🎨 **Clean Visual Interface** - Green bounding boxes with confidence scores

## Applications

-  **Assistive Technology** - Vision assistance for visually impaired
- 🏢 **Surveillance** - Automated monitoring systems
- 🏭 **Industrial Safety** - Real-time hazard detection
- 🎓 **Education** - Computer vision learning tool
- 🏠 **Smart Home** - Intelligent home monitoring

## Project Insights
- Successfully integrates computer vision (YOLOv8) with text-to-speech functionality
- Implements efficient frame processing by resizing before detection
- Uses threading to prevent audio feedback from blocking the main detection loop
- Provides both visual and auditory feedback for detected objects
- Handles edge cases like no detections or processing errors gracefully

## Features
- Real-time object detection using YOLOv8
- Selective tracking of specific object classes
- Voice announcements for new detections
- Visual bounding boxes and labels
- GPU acceleration support
- Responsive interface with 'q' key to exit
- Error handling for webcam access and processing issues

## Final Conclusion
This project successfully demonstrates a working integration of real-time object detection with voice feedback. The system effectively identifies objects in a webcam feed and provides auditory announcements when new objects appear, making it potentially useful for accessibility applications or situations where visual attention cannot be dedicated to a screen. The code is structured to handle various edge cases and optimized for performance through frame resizing and selective class detection. Future enhancements could include more sophisticated tracking, custom object training, or integration with smar
