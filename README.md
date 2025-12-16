# Elder Souls RPG

Elder Souls RPG is a **command-line role-playing game developed in C++**, designed to simulate the core mechanics of classic tabletop RPGs. The project heavily applies **object-oriented programming concepts**, especially **inheritance and polymorphism**, to model characters, combat styles, and game progression.

---

## Overview

In Elder Souls RPG, the player creates their own character and embarks on a journey across **three distinct worlds**. Each character class directly affects combat style, intelligence, resistance, and other attributes, shaping how the game unfolds.

The adventure is driven by:
- Battles against enemies  
- Logical challenges and riddles  
- Dice-based mechanics that define outcomes, closely mimicking tabletop RPG dynamics  

---

## Platform Compatibility

This project was developed **exclusively for Windows**.

It uses Windows-specific libraries such as:
- `<windows.h>`
- `<conio.h>`
- `<mmsystem.h>`

Because of this, the project **will not compile or run on Linux or macOS** without significant modifications.

No external libraries are required. All dependencies are part of the standard C++ library or native Windows APIs.

---

## Core Features

- Fully text-based RPG played in the terminal  
- Multiple character classes with unique attributes and behaviors  
- Inheritance and polymorphism used to model characters and enemies  
- Dice-based decision system inspired by tabletop RPGs  
- Three different worlds with unique challenges  
- Turn-based combat system  
- Character leveling system based on experience gained  
- Magical items that enhance specific abilities  

---

## Gameplay Mechanics

- **Character Creation:** The player selects a class that determines stats and playstyle  
- **Dice System:** Actions and outcomes are influenced by dice rolls  
- **Combat:** Turn-based battles where class attributes affect performance  
- **Progression:** Characters gain experience, level up, and improve stats  
- **Items:** Magical items provide strategic advantages and skill enhancements  

---

## Technologies Used

- **Language:** C++  
- **Paradigm:** Object-Oriented Programming (OOP)  
  - Inheritance  
  - Polymorphism  
- **Interface:** Command Line Interface (CLI)

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/cyberdebb/Elder-Souls-RPG.git
   ```
2. Run the ```ElderSoulsRPG.exe``` executable file **OR** Compile the project:
  ```bash
  cd src
  g++ main.cpp -o ElderSoulsRPG
  ```
3. Run the game:
  ```bash
  ./ElderSoulsRPG
