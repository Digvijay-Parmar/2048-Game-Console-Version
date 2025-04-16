# End-Sem project: 2048

## Group Name: "SKDK"
  - PARMAR DIGVIJAY :- 202401444
  - SHLOK GOHEL :- 202401476
  - KARAN SHUKLA :-202401479
   - KUSH PATEL :- 202401448
 ---
✨ **Why this project?**

-   A perfect blend of logic and simplicity — the addictive puzzle game *2048*!  
- Built from scratch to practice **Object-Oriented Programming** in C++.  
 -  Focused on **game mechanics**, **file handling**, and **input handling**.  
  -   A simple and sober project that reinforces core concepts taught in the initial lectures, such as 📦 classes, 🧬 inheritance, and 🗃️ basic file handling.

---
---


## :dart: About

### What is The 2048 Game?

It's a type of “sliding block puzzle” — think Threes!, on which 2048 is based, or the old-timey game klotski — that's played on an almost Sudoku-like grid. Like Sudoku, it also involves some math. The object of the game is to combine the numbers displayed on the tiles until you reach 2048.

## 🧾 Code
 

| <a href="https://github.com/rahul-badgujar/2048-Game-Console-Version" target="_blank"><img src="https://github.com/rahul-badgujar/EShopee-Flutter-eCommerce-App/blob/main/illustrations/source_code_icon.png?raw=true" width="90px"></a> | <a href="https://github.com/rahul-badgujar/2048-Game-Console-Version/blob/main/bin/Release/2048%20Game%20Console%20Version.exe" target="_blank"><img src="https://github.com/rahul-badgujar/EShopee-Flutter-eCommerce-App/blob/main/illustrations/application_icon.png?raw=true" width="90px"></a> |
|:---:|:---:|
|            Source Code            |            Download Executable             |


### 🔹 `main.cpp` - Entry Point

- Acts as the starting point of the 2048 game.
- Includes the `Game.h` header which contains the `Game` class.
- Calls the static method `Game::startGame()` to launch the game.
- No object instantiation is needed as all methods in `Game` are static.
- Uses `EXIT_SUCCESS` to return 0 on successful execution.
- Relies on the `rlutil.h` library for enhanced console UI features like:
  - Colored text
  - Cursor movement
  - Delays for animations

 
### 🔹 `game.cpp` - Main file
- Contains all the important parts of the game.
- - Includes several key libraries:
  - `<fstream>`, `<string>`, `<iomanip>`, `<time.h>` — for file I/O, formatting, and randomness.
  - Custom headers: `Utilities.h`, `Debugger.h`, and `Player.h`.
- Handles the game loop, including starting the game, drawing the board, and managing user inputs.
- Core logic of the game resides here, making it the heart of the project.
- Responsible for game state management, ensuring that the game progresses correctly from start to finish.
- Controls the spawning of new tiles and updating of the board state after every move.
- Handles the scoring system, updating the score after each successful move.
- Includes functions to check for game over conditions or when the player wins.
- Integrates with other components like input handling, display rendering, and game logic.

### 🔹 `player.cpp` – Implementation File

- Implements the methods declared in `player.h`.
- Handles initialization and manipulation of player data.

#### ✅ Key Functionalities:
- **Constructor (`Player()`):**
  - Sets default name to `"NA"` and score to `0`.

- **Destructor (`~Player()`):**
  - Currently empty but declared for future use and proper cleanup.

- **Score Methods:**
  - `getPlayerScore()`: Returns current score.
  - `setPlayerScore()`: Sets a new score.
  - `addToPlayerScore()`: Increments score by the given value.

- **Name Methods:**
  - `getPlayerName()`: Returns a pointer to the player name.
  - `setPlayerName()`: Copies the given name to `playerName`.

---

### 📝 Summary

The `Player` class acts as a simple data model for players. It encapsulates the player's name and score, provides easy access and modification methods, and plays a key role in tracking player progress during the game.


### 🔹 `Debugger.cpp` – Implementation File

- Provides the definition for the `handleException` method.

#### ✅ Key Functionalities:
- **handleException():**
  - Prints an error message using `std::cerr`.
  - If `toExit` is `true`:
    - Clears the console screen.
    - Displays termination message using `Utilities::print()`.
    - Exits the program with failure status (`exit(EXIT_FAILURE)`).

---

### 📝 Summary

The `Debugger` class acts as a centralized error-handling mechanism to:
- Catch and display unexpected errors.
- Optionally terminate the program safely.
- Improve code maintainability and debugging support.

Useful during development and runtime to track down critical failures or misbehavior in game logic or utilities.

### 🔹 `Utilities.cpp` – Implementation File

Contains definitions of the utility methods declared in the header.

#### ✅ Key Functionalities:

- **print(...)**  
  - Simulates animated typing by printing each character with a delay.
  - Changes the text color using `rlutil::setColor`.
  - Accepts optional parameters:
    - `lineEnd`: if `true`, ends the line after the message.
    - `color`: sets the text color.
    - `delay`: delay in milliseconds between characters.
  - Resets to the default text color after printing.

- **getRandomNumber(leftLimit, rightLimit)**  
  - Returns a pseudo-random integer in the specified range.
  - Uses `rand()` with proper bounds calculation.

---
# rlutil.h – Console Utility Library for C++

`rlutil.h` is a lightweight, header-only C++ utility library for building colorful, interactive terminal applications. It supports basic console operations like screen clearing, cursor movement, color control, and non-blocking input—perfect for text-based games like 2048 or Pacman.

---

## 🚀 Features

- ✅ **Cross-platform**: Works on Windows, Linux, and macOS.
- 🎨 **Colorful output**: Easily change text and background colors.
- 🖱 **Cursor control**: Move the cursor, hide/show it.
- 🧹 **Screen manipulation**: Clear or modify console display.
- ⌨️ **Keyboard input**: Detect key presses (supports arrow keys, etc.)

---


**📘 What have We Learned**

-  Applied **Object-Oriented Programming (OOP)** principles like encapsulation, inheritance, and abstraction.
- 🗃 Used **file handling** for saving high scores or game states.
-  Improved problem-solving skills by debugging, optimizing logic, and handling edge cases.
-  Managed real-time **keyboard inputs** to control game flow smoothly.
-  Practiced breaking down complex problems into modular, manageable code components.

---

**Conclusion**
- That is all about end-sem project, we have learnt many things from this project as metion above and not to forget we have learn much abot Git and Github during All this course. So Thank's a lot for giving these types of unique projects and hope you like this one from our side.
