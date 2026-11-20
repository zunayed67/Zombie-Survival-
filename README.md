# 🧟 Zombie Survival: Last Stand

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pygame](https://img.shields.io/badge/Pygame-2D%20Game%20Engine-00A86B?style=for-the-badge)](https://www.pygame.org/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_USERNAME/Zombie-Survival-Last-Stand)

A **2D top-down zombie survival shooter** built with **Python** and **Pygame**. Fight through escalating waves of zombies, manage your ammunition under pressure, navigate a scrolling world, and chase the highest score before your health hits zero.

---

## 📖 Table of Contents

- [About the Game](#-about-the-game)
- [Key Features](#-key-features)
- [Gameplay & Controls](#-gameplay--controls)
- [Tech Stack & Computer Graphics Concepts](#-tech-stack--computer-graphics-concepts)
- [Project Structure](#-project-structure)
- [Installation & Setup](#-installation--setup)
- [Roadmap & Future Improvements](#-roadmap--future-improvements)
- [Project Objective](#-project-objective)
- [Author](#-author)

---

## 🎮 About the Game

**Zombie Survival: Last Stand** places you in a top-down survival arena overrun by relentless zombies. Using responsive keyboard movement and mouse aiming, you must line up shots, manage reloads, and outmaneuver incoming hordes as each wave grows larger and faster.

The goal is straightforward: **eliminate zombies, dodge attacks, rack up points, and survive as many waves as possible.**

---

## ✨ Key Features

- **Smooth 4-Directional Movement:** Move freely around the arena with responsive keyboard controls.
- **360° Mouse Aiming:** Aim toward the cursor in real time.
- **Gunplay & Reloading:** Fire your pistol with limited ammo and tactical reloads.
- **Zombie Pursuit AI:** Zombies detect the player and close in continuously.
- **Health & Survival Loop:** Taking zombie hits drains health—reach zero health and it's game over.
- **Escalating Wave System:** Survive wave after wave with tougher, denser zombie spawns.
- **Score Tracking:** Earn points for every zombie eliminated.
- **Scrolling Camera:** Viewport smoothly tracks the player across the world.
- **Complete Game States:** Includes **Main Menu**, **Active Gameplay**, **Pause**, and **Game Over** screens.

---

## 🕹️ Gameplay & Controls

Start armed with a pistol and a finite supply of ammo. Zombies spawn around the world and converge on your position—keep moving, watch your magazine count, and clear threats before they swarm you. As your score climbs, wave intensity ramps up.

### Controls

| Input | Action |
| :--- | :--- |
| `W` / `↑` | Move Up |
| `S` / `↓` | Move Down |
| `A` / `←` | Move Left |
| `D` / `→` | Move Right |
| **Mouse Cursor** | Aim Weapon |
| **Left Mouse Button** | Shoot |
| `R` | Reload Weapon |
| `P` / `ESC` | Pause / Resume Game |
| `ENTER` | Restart After Game Over |

---

## 🛠️ Tech Stack & Computer Graphics Concepts

### Technologies Used

| Technology | Role in Project |
| :--- | :--- |
| **Python 3** | Core programming language and game logic |
| **Pygame** | 2D rendering, input handling, and game loop |
| **Pygame `Vector2`** | Direction vectors, distance checks, and velocity math |
| **Pygame `Rect`** | Hitboxes and collision detection |
| **Pygame `transform`** | Scaling and rotating sprites |
| **Pygame `mixer`** | Sound effects and background audio |
| **Git & GitHub** | Version control and repository hosting |

### Computer Graphics Concepts Applied

- **2D Transformations:** Translation, rotation, and scaling of sprites and projectiles.
- **Collision Detection:** Checking overlaps between bullets, zombies, and the player.
- **Vector Mathematics:** Computing movement direction, normalized velocity, and target distance.
- **Sprite Rendering:** Drawing, updating, and managing active entities each frame.
- **Animation:** Handling movement and character visual states.
- **Camera Scrolling:** Offset rendering so the camera follows the player across world space.
- **Coordinate Systems:** Converting and managing **world coordinates** vs. **screen coordinates**.

---

## 📁 Project Structure

```text
Zombie-Survival-Last-Stand/
├── main.py            # Entry point to launch the game
├── settings.py        # Global constants, colors, and tuning values
├── game.py            # Main game loop, wave logic, and screen states
├── entities.py        # Player, zombie, and projectile classes
├── camera.py          # Scrolling camera offset logic
├── requirements.txt   # Python package dependencies
├── README.md          # Project documentation
└── assets/
    ├── images/        # Sprites and visual assets
    ├── sounds/        # Sound effects and music
    └── fonts/         # Custom UI typography
