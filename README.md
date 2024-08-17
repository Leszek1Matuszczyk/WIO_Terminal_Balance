# Wio Terminal Balance Ball Game

This repository contains the source code for a simple balance ball game developed for the Wio Terminal. The game uses the Wio Terminal's built-in accelerometer and TFT display to create an interactive experience where the player controls a ball by tilting the device.

## Features

- Control a ball on the screen by tilting the Wio Terminal.
- Avoid the moving rectangles to keep playing. If the ball collides with a rectangle, the game ends.
- The game uses the Wio Terminal's TFT display to render the ball and obstacles in real-time.

## Hardware Requirements

- Wio Terminal (with built-in accelerometer and TFT display)

## Software Requirements

- Arduino IDE
- Libraries:
  - LIS3DHTR
  - TFT_eSPI
  - Free_Fonts

## Installation and Setup

1. Clone the repository:
   https://github.com/Leszek1Matuszczyk/WIO_Terminal_Balance
2. Install the required libraries:
- Open the Arduino IDE.
- Go to "Sketch" -> "Include Library" -> "Manage Libraries".
- Search for and install the following libraries:
  - LIS3DHTR
  - TFT_eSPI
  - Free_Fonts

3. Upload the code:
- Connect your Wio Terminal to your computer.
- Open the `Wio_Terminal_Balance_Ball.ino` file in the Arduino IDE.
- Select "Seeeduino Wio Terminal" as the board.
- Select the appropriate port.
- Click the upload button.

## How to Play

- Start the game: Once the code is uploaded, the game will start automatically.
- Control the ball: Tilt the Wio Terminal to move the ball around the screen.
- Avoid rectangles: Navigate the ball to avoid colliding with the moving rectangles.
- Game over: If the ball hits a rectangle, the game ends and a "Game Over" screen is displayed.
- Restart: To play again, press the reset button on the Wio Terminal.

## Contributions

Contributions are welcome! Feel free to fork this repository and submit a pull request if you have any improvements or features to add.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements

- This game was developed using the Wio Terminal's built-in hardware features.
- Special thanks to the developers of the `TFT_eSPI` and `LIS3DHTR` libraries for enabling the display and accelerometer functionality.

## Author

Leszek Matuszczyk - [GitHub Profile](https://github.com/Leszek1Matuszczyk)
