# End-Sem project: 2048

## Group Name: "SKDk"
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



**📘 What We Learned**

-  Applied **Object-Oriented Programming (OOP)** principles like encapsulation, inheritance, and abstraction.
- 🗃 Used **file handling** for saving high scores or game states.
-  Improved problem-solving skills by debugging, optimizing logic, and handling edge cases.
-  Managed real-time **keyboard inputs** to control game flow smoothly.
-  Practiced breaking down complex problems into modular, manageable code components.

---

**Conclusion**
- That is all from our side hope you like this.
