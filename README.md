# Voice-Enabled-Real-Time-Object-Tracking-Using-Image-Processing

## Project Objective
To create a real-time object detection and tracking system that combines computer vision with voice feedback. The system uses a webcam feed to identify objects from predefined classes and provides audio announcements when new objects are detected or their counts increase, making it accessible for visually impaired users or hands-free applications.

## Process
1. Setup: Initialize the YOLOv8 model for object detection with GPU acceleration if available
2. Video Capture: Access the webcam feed using OpenCV
3. Frame Processing:
- Resize frames for efficient processing
- Run object detection using YOLOv8
- Filter detections to only selected classes
4. Tracking & Analysis:
- Compare current detections with previous frame
- Identify new objects or count increases
5. Voice Feedback:
- Use text-to-speech to announce detected objects
- Implement threading for non-blocking audio feedback
6. Visualization:
- Draw bounding boxes and labels on detected objects
- Display the annotated video stream

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
