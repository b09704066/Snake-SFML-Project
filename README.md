# Snake-SFML-Project

**MUST HAVE SFML LIBRARY TO RUN THIS PROJECT**

**INCLUDE DEV CPP IN THE PARENT FILE TO RUN**
(refer to the following pic)

<img width="411" alt="截圖 2025-02-28 下午5 47 02" src="https://github.com/user-attachments/assets/bcefe1d6-9bd1-4949-a12c-c5a5583729a6" />

## Project Description
This project aims to deliver the best strategy for the snake game. That is, to maximize the points (eating dots) while preventing dying (colliding with the wall or enemies). This project utilizes SFML framework and demonstrates my ability to implement Entity Component System (ECS).

## File Structure
```
cmake-build-debug/
dev_cpp/
src/
├── Config.h                    # Configuration constants
├── ConstantDirectionController.h/.cpp  # controllers moving in a fixed direction
├── CustomController.h/.cpp      # Custom controller logic
├── DirectionType.h              # Enum for movement directions
├── Game.h/.cpp                  # Core game logic and mechanics
├── GUI.h/.cpp                   # GUI implementation (if enabled)
├── ISnakeController.h           # Interface for all snake controllers
├── main.cpp                     # Entry point of the game
├── PlayerController.h/.cpp      # Player-controlled snake logic
├── Position.h/.cpp              # Positioning system for the snake and food
├── Snake.h/.cpp                 # Snake class defining movement and behavior
├── StraightForwardController.h/.cpp  # controller moving straight
├── CMakeLists.txt               # CMake build configuration
```

## Installation & Compilation
### Prerequisites
- A C++ compiler supporting C++17 or later
- CMake for building the project

### Build Instructions
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/snake-game.git
   cd snake-game
   ```
2. Create a build directory and compile:
   ```sh
   mkdir build && cd build
   cmake ..
   make
   ```
3. Run the game:
   ```sh
   ./snake_game
   ```

## How to Play
1. Run `snake_game`
2. Select a test mode (A, B, or C)
3. Select a controller mode (0: Player, 1: AI, 2: Fast-forward AI)
4. Play using the keyboard (if using PlayerController) or watch the AI in action

## Future Improvements
- Enhance GUI with more interactive elements
- Implement additional AI strategies
- Add multiplayer support

## License
This project is open-source under the MIT License.



<img width="958" alt="截圖 2025-02-28 下午5 41 47" src="https://github.com/user-attachments/assets/efef9ebf-e2fb-43ae-b08c-d9adafb7538b" />

<img width="956" alt="截圖 2025-02-28 下午5 42 03" src="https://github.com/user-attachments/assets/01b817f1-e6cb-4412-b265-9c0bbac2850d" />


