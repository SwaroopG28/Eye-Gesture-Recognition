# Eye Gesture Recognition

## Abstract
This application utilizes Python and OpenCV to enable cursor movement on a computer screen through eye gestures. It serves as an interactive module, providing an alternative to touchscreen technology. By detecting facial movements in real-time via a webcam, users can control the cursor and perform actions such as clicking and scrolling.

## Features
- **Cursor Control**: Move the cursor using a point on the user's face.
- **Click Operations**: Implement left and right clicks through eye winks.
- **Scrolling Functionality**: Use squeezed eyes to enable scrolling.
- **Voice Feedback**: Receive audio prompts for actions (e.g., light control).

## Code Structure
- `Main.py`: The main script that captures video input and processes eye gestures.
- `eye_detect.py`: Contains the class for handling eye blink detection and voice feedback.


## Acknowledgments
- OpenCV for real-time computer vision capabilities.
- dlib for facial landmark detection.
- imutils for convenience functions.
