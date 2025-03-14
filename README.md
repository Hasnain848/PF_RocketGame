**Space Shooter Game Report**

## 1. Introduction
This is a simple console-based Rocket Shooting Game developed using the C language. The game features a player-controlled rocket that can shoot bullets at enemy ships. It includes various functionalities such as movement, shooting, collision detection, and score management. Players interact with the game via the keyboard ('A' and 'D' for movement, Spacebar to shoot, 'Q' to quit).

---

## 2. Features
- 🚀 **Player Movement:** The rocket moves left and right using the 'A' and 'D' keys.
- 🎯 **Bullet Shooting:** Press the spacebar to shoot bullets at enemies.
- 👾 **Enemy Movement:** Enemies spawn at random positions and move downwards.
- 🏆 **High Scores:** The top 5 highest scores are saved and displayed.
- 📜 **Game Instructions:** Clear instructions for player actions.
- 🎵 **Sound Effects:** Background music and in-game sounds (via the mciSendString function, using MP3 files).

---

## 3. How to Play
1. Use the 'A' or 'D' keys to move your rocket left or right.
2. Press the Spacebar to shoot bullets at the enemies.
3. Enemies move downward; each time you hit one, your score increases by 10.
4. The game ends when an enemy collides with the player’s rocket.
5. Press 'Q' to quit the game.

---

## 4. Implementation Details
This project implements several core concepts of C programming, including:

- 🏗 **Functions:** Used to modularize the program (e.g., menu navigation, game logic, etc.).
- 🏛 **Structures:** Used to store the player’s rocket, bullets, and enemies' positions, as well as high scores.
- 🎯 **Pointers:** Utilized for handling dynamic memory and structure manipulation.
- 🎲 **Random Number Generation:** For spawning enemies at random positions.
- 📂 **File Handling & Score Management:** Storing and retrieving high scores using file I/O.
- 🔁 **Control Flow:** Implementation of conditionals, loops, and user inputs for dynamic game behavior.
- 💥 **Game Logic:** Collision detection between bullets and enemies, and the game-over condition.
- 🎵 **Sound & Menu Management:** Background music, sound effects, and structured navigation for user-friendly interaction.

---

## 5. Project Members & Task Distribution

### Filing and Score Management:
- **Hasnain [24K-0516]**

### Game Logic Design:
- **Arham Usman [24K-1016]**
- **Muhammad Ibrahim [24K-0649]**

### Menu and Sound:
- **Obaid-Ullah [24K-0793]**

---

## 6. Screenshots
![Main Menu](https://github.com/Hasnain848/PF_RocketGame/blob/main/Images/pro1.png?raw=true)
![Gameplay](https://github.com/Hasnain848/PF_RocketGame/blob/main/Images/pro2.png?raw=true)
![High Scores](https://github.com/Hasnain848/PF_RocketGame/blob/main/Images/pro3.png?raw=true)
![Instructions](https://github.com/Hasnain848/PF_RocketGame/blob/main/Images/pro4.png?raw=true)
![Task Distribution](https://github.com/Hasnain848/PF_RocketGame/blob/main/Images/pro5.png?raw=true)


