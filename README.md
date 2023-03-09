# Snake_MPU

## Description

This project uses an MPU sensor to control a snake game built with Python using object-oriented programming (OOP) principles. The goal is to use the MPU sensor to control the direction of the snake as it moves around the screen, eating food and growing longer. The project is composed of two main parts: an Arduino sketch that reads data from the MPU sensor and sends it to the Python code, and a Python script that runs the game and uses the MPU data to control the snake.

## Prerequisites

To run this project, you will need:

- An MPU sensor
- An Arduino board
- Python 3.x installed on your computer
- Pygame library installed on your computer
- Arduino IDE installed on your computer

## Setup

1. Connect the MPU sensor to the Arduino using the wiring diagram provided in the "Arduino" folder.
2. Upload the Arduino sketch provided in the "Arduino" folder to the Arduino board using the Arduino IDE.
3. Open a terminal or command prompt window and navigate to the folder containing the Python code.
4. Run the Python notebook "Easy_Snake.ipynb" or "Hard_Snake.ipynb" depending on the desired level of difficulty.
5. Run the Python notebook "Control_Code_Snake.ipynb" .
6. Enjoy the game!

## Usage

To play the game, hold the MPU sensor in your hand and tilt it in the direction you want the snake to move. The game will continue until the snake hits a wall or its own body. To exit the game, click the window's `X` button.

## Acknowledgements

This project was inspired by the classic Snake game and the MPU6050 library for Arduino. Special thanks to the developers of the Pygame and Pyserial libraries for Python.

