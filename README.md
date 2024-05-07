# OpenCV Air Canvas and Face Detection Project

This project utilizes OpenCV and Mediapipe to create an air canvas, detect faces, and calculate the screen-to-hand distance.

## Features
1. **Air Canvas:** Draw on a virtual canvas by moving your hand in front of the camera.
2. **Face Detection:** Detect and highlight faces in the video stream.
3. **Screen-to-Hand Distance:** Calculate the distance between your hand and the camera in real-time.

## Requirements
- Python 3.x
- OpenCV
- Numpy
- Mediapipe
- Collections module

## Installation
1. Clone or download the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.

## Usage
1. Run `main.py` to start the application.
2. Use your hand to draw on the air canvas.
3. Face detection will be automatically applied to the video stream.
4. The screen-to-hand distance will be displayed on the screen.

## Files
- `main.py`: Main script for running the application.
- `requirements.txt`: List of dependencies for easy installation.

## Configuration
- Modify `focal_length` and `real_hand_length` in `main.py` for accurate distance calculations based on your camera setup and known hand dimensions.

## Credits
- This project was inspired by various OpenCV tutorials and Mediapipe documentation.

## License
This project is licensed under the [MIT License](LICENSE).
