# Hand Cursor Control (Computer Vision)

This project allows you to control the cursor using your hand movements captured by a webcam. The solution uses `mediapipe` for hand landmark detection and `pyautogui` for cursor control.

## Requirements

- Python 3.x
- `mediapipe` library
- `opencv-python` library
- `pyautogui` library
- A webcam

## Installation

1. Install Python 3.x from the official [Python website](https://www.python.org/).

2. Install the required libraries:
    ```sh
    pip install mediapipe opencv-python pyautogui
    ```

## Usage

1. Save the following script as `hand_cursor_control.py`:

2. Open a terminal or command prompt and navigate to the directory where you saved the script.

3. Run the script:
    ```sh
    python hand_cursor_control.py
    ```

4. Allow webcam access if prompted. The script will open a window showing the webcam feed. Move your hand in front of the webcam to control the cursor with the index finger.

5. To exit the script, press the `Esc` key.
