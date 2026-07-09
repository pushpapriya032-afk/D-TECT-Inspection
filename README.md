# D-TECT Inspection

## Overview

D-TECT Inspection is an AI-powered real-time surveillance web application developed to detect suspicious objects using a live camera feed. The project uses TensorFlow.js and the COCO-SSD object detection model to identify selected objects and trigger alerts instantly.

## Features

- 🎥 Live Camera Monitoring
- 🤖 Real-Time Object Detection using COCO-SSD
- 🚨 Instant Alert System
- 🔊 Audio Alert on Detection
- 📸 Automatic Snapshot Capture
- 📱 SMS Notification Support
- 📊 Detection Dashboard
- 💻 Responsive User Interface

## Technologies Used

- HTML5
- CSS3
- JavaScript
- TensorFlow.js
- COCO-SSD Model
- Local Storage

## Project Workflow

1. User starts the live camera.
2. The AI model loads automatically.
3. The camera continuously scans the surroundings.
4. When the selected object is detected:
   - An alert sound is played.
   - A snapshot is captured.
   - An SMS alert is triggered (if configured).
   - The detection is recorded on the dashboard.

## Folder Structure

```
D-TECT-Inspection/
│── final1.html
│── weapon.html
│── dashboard.html
│── alert message.html
│── README.md
```

## Future Enhancements

- Face Detection
- Custom Weapon Detection using YOLO
- Cloud Database Integration
- User Authentication
- AI-Based Threat Analysis

## How to Run

1. Download or clone this repository.
2. Open the project in Visual Studio Code.
3. Install the Live Server extension (optional).
4. Open **final1.html** (or **index.html** if renamed).
5. Allow camera permission.
6. Click **Start Detection**.

## Author

**Pushpa Priya**

Information Technology Student

## License

This project is developed for educational and learning purposes.
