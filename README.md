Virtual Mouse Control with Hand Gesture Recognition

This is a Python program that allows you to control the mouse cursor and simulate mouse clicks using hand gestures captured from your webcam. It uses OpenCV for capturing video frames, the MediaPipe library for hand detection and tracking, and PyAutoGUI for simulating mouse movements and clicks. You can use this program to control your computer's mouse cursor and perform actions like clicking by moving your hand in front of your webcam.

## Prerequisites

Before you can use this program, you need to have the following dependencies installed:

- Python 3.x
- OpenCV (`cv2`)
- MediaPipe (`mediapipe`)
- PyAutoGUI (`pyautogui`)

You can install these dependencies using `pip`. For example:

```bash
pip install opencv-python mediapipe pyautogui
```

## Usage

1. Clone or download this repository to your local machine.
2. Make sure your webcam is connected and functional.
3. Run the `virtual_mouse.py` script:

```bash
python virtual_mouse.py
```

4. The program will open a window showing the webcam feed with hand landmarks and a circle around your index and thumb fingers.
5. To move the mouse cursor, simply move your hand and keep your index finger within 20 pixels vertically of your thumb finger.
6. To click, bring your index finger and thumb finger close (within 20 pixels) or overlap them, and the program will simulate a mouse click.

You can customize the threshold values for click detection by modifying the `20` and `100` values in the code according to your preferences.

## Closing the Program

To exit the program, simply close the window displaying the webcam feed, or press `Ctrl+C` in the terminal where the program is running.

## Troubleshooting

- If the program is not working as expected, make sure you have all the dependencies installed and that your webcam is functioning correctly.
- Ensure that there is adequate lighting in the room for better hand detection.
- You may need to adjust the threshold values for click detection to match your hand movement.

## Disclaimer

This program is intended for educational and experimental purposes and may not work perfectly in all scenarios. Use it responsibly and be aware of potential limitations in hand tracking accuracy and gesture recognition.

## License

This program is provided under the MIT License. See the [LICENSE](LICENSE) file for details.

If you encounter any issues or have suggestions for improvements, please feel free to create an issue or pull request on the [GitHub repository](https://github.com/yourusername/your-repo).

Happy hand gesture-controlled computing!
