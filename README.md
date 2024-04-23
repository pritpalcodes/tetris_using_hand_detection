# tetris_using_hand_detection**# Tetris Hand Gesture Control

This project is a Tetris game implemented in Python using the Pygame library, with an added feature of controlling the game using hand gestures captured from a webcam. It utilizes the OpenCV and Mediapipe libraries for hand tracking and gesture recognition.

## Requirements

To run this project, you need to have the following dependencies installed:

- Python 3.9
- Pygame
- OpenCV
- Mediapipe

You can install these dependencies using pip:

```
pip install pygame opencv-python mediapipe
```

## How to Play

1. Run the script.
2. Ensure your webcam is connected and positioned properly.
3. Use hand gestures to control the falling Tetris shapes:
   - **Left Gesture:** Move the current piece left.
   - **Right Gesture:** Move the current piece right.
   - **Rotate Gesture:** Rotate the current piece.
   - **Down Gesture:** Accelerate the fall of the current piece.
4. Arrange the falling Tetris shapes to fill complete rows.
5. Each completed row will be cleared, and you will earn points.
6. The game ends when the pieces stack up to the top of the grid.

## Controls

- **Left Arrow Key:** Move the current piece left.
- **Right Arrow Key:** Move the current piece right.
- **Down Arrow Key:** Accelerate the fall of the current piece.
- **Up Arrow Key:** Rotate the current piece.

## Features

- Hand gesture control using a webcam.
- Traditional keyboard controls are also available.
- Score tracking and level progression.
- Next shape preview for strategic planning.

## Acknowledgments

- This project is based on the classic Tetris game.
- Hand tracking and gesture recognition are powered by the OpenCV and Mediapipe libraries.

## Author

- [Pritpal Singh](www.linkedin.com/in/oye-pritpal)

Enjoy playing Tetris with a twist of gesture control! If you encounter any issues or have suggestions for improvements, feel free to reach out.
