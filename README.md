# Pong

**Pong** is a minimalist and cross-platform Pong game developed using the Raylib library. It features smooth controls, a basic CPU opponent AI, and classic arcade gameplay. This lightweight game is perfect for learning game development fundamentals or enjoying a quick nostalgic match.

![pong-screenshot](https://github.com/user-attachments/assets/25bbf285-d081-449f-966b-ea4b7628bc1d)

## Features of the Pong Raylib Game

### Cross-Platform Compatibility
- Runs smoothly on Windows, macOS, and Linux thanks to Raylib’s cross-platform support.

### Simple and Clean Gameplay
- Classic Pong mechanics with player paddle controlled by arrow keys.
- CPU paddle with basic AI follows the ball.
- Scores tracked and displayed on the screen.

### Easy to Build and Run
- Minimal dependencies, just requires Raylib to compile and run.
- Lightweight and fast execution.

### Source Code Highlights
- Uses classes for Ball and Paddle objects.
- Handles collision detection between ball and paddles.
- Responsive input handling with smooth paddle movement.
- Randomized ball reset direction after each score.

## Building the Pong Game from Source

To build and run **Pong** from source, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ali-begic/pong-raylib.git
   cd pong-raylib

2. **Install Raylib:**
   - Follow the official Raylib installation guide for your platform: https://www.raylib.com/  
   - Make sure your compiler can find raylib headers and libraries.

3. **Build the Game:**

   Example build commands (adjust for your platform and compiler):

   - On Linux/macOS (with gcc/clang):
     ```bash
     g++ src/main.cpp -o pong -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
     ```

   - On Windows (using MinGW):
     ```bash
     g++ src/main.cpp -o pong.exe -lraylib -lopengl32 -lgdi32 -lwinmm
     ```

4. **Run the Game:**
   ```bash
   ./pong    # or pong.exe on Windows

## Controls

- **Player Paddle:** Up and Down arrow keys.
- **Objective:** Score points by making the ball pass the CPU paddle.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests for bug fixes, improvements, or new features.

## License

This project is licensed under the Apache-2.0 license - see the [LICENSE](LICENSE) file for details.

---

Thank you for checking out **Pong** — a minimalistic, enjoyable game powered by Raylib!
