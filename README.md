# Hand Tracking with MediaPipe

This project demonstrates hand tracking using MediaPipe and OpenCV in Python. It includes two scripts: one for basic hand tracking and another that encapsulates functionality within a `handDetector` class.

## Features

- **Real-time hand tracking** using MediaPipe.
- **Detection of hand landmarks** and their positions.
- **FPS display** to monitor performance.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ByakkoHvsc/Hand-tracking.git

2. Install Dependencies:
   ```bash
   pip install opencv-python mediapipe

## Usage

### Basic Hand Tracking

1. Navigate to the project directory.

2. Run the script:
   ```bash
   python HandTrackingMin.py


## Hand Tracking with handDetector Class

Hand Tracking with ` handDetector ` Class

1. Navigate to the project directory.

2. Run the script:
   ```bash
   python HandTrackingModule.py
## How It Works

**File 1:** Basic Hand Tracking

1. Captures video from the webcam.
2. Converts the frame to RGB and processes it with MediaPipe to detect hand landmarks.
3. Draws landmarks and connections on the image.
4. Calculates and displays FPS.

   
**File 2:** Hand Tracking with handDetector Class
1. Encapsulates hand tracking functionality in a handDetector class.
2. Provides methods to find hands and their positions.
3. Draws landmarks and displays FPS.
4. Allows customization of detection and tracking confidence levels.

## Contributing
Contributions are welcome! Please fork the repository, make changes, and submit pull requests.
