# Flappy Bird Clone using Python & Pygame

A recreation of the popular **Flappy Bird** game developed using **Python** and **Pygame**. This project demonstrates core game development concepts such as event handling, collision detection, sprite management, procedural obstacle generation, and real-time score tracking.

---

## Project Overview

The objective of this project was to build a fully functional 2D arcade game while gaining hands-on experience with Python game development. Players control a bird that must navigate through randomly generated pipes without colliding with obstacles or the ground.

This project helped strengthen my understanding of game loops, physics simulation, asset handling, and interactive application development.

---

## Features

- Responsive keyboard controls
- Gravity and flap-based movement system
- Infinite gameplay with procedurally generated pipes
- Real-time score tracking
- Collision detection system
- Sound effects integration
- Welcome screen before gameplay
- Smooth frame-rate controlled execution
- Dynamic obstacle generation

---

## Technology Stack

**Programming Language**
- Python

**Framework**
- Pygame

**Assets**
- PNG Images
- WAV Audio Files

**Tools**
- Git
- GitHub
- VS Code

---

## Project Structure

```text
Flappy-Bird/
│
├── flappy_birds.py
│
├── gallery/
│   ├── sprites/
│   │   ├── bird.png
│   │   ├── background.png
│   │   ├── pipe.png
│   │   ├── base.png
│   │   ├── message.png
│   │   ├── 0.png
│   │   ├── 1.png
│   │   ├── ...
│   │   └── 9.png
│   │
│   └── audio/
│       ├── die.wav
│       ├── hit.wav
│       ├── point.wav
│       ├── swoosh.wav
│       └── wing.wav
│
├── README.md
└── .gitignore
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/shreyas2007-goyal/flappy-bird-project.git
cd flappy-bird
```

### Create a Virtual Environment

```bash
python -m venv penv
```

### Activate the Virtual Environment

**Windows**

```bash
penv\Scripts\activate
```

**Linux / macOS**

```bash
source penv/bin/activate
```

### Install Dependencies

```bash
pip install pygame
```

---

## Running the Game

```bash
python flappy_birds.py
```

---

## Controls

| Key | Action |
|------|---------|
| Spacebar | Flap Bird |
| Up Arrow | Flap Bird |
| ESC | Exit Game |

---

## Technical Concepts Implemented

### Game Loop Architecture

A continuous loop handles:

- Event processing
- Physics calculations
- Rendering graphics
- Updating game objects
- Collision checks

### Collision Detection

The game detects collisions between:

- Bird and upper pipes
- Bird and lower pipes
- Bird and ground
- Bird and screen boundaries

### Procedural Obstacle Generation

Pipes are generated dynamically with randomized heights to create a unique gameplay experience during every run.

### Physics Simulation

Implemented mechanics include:

- Gravity
- Vertical acceleration
- Flapping force
- Velocity limits

### Score Management

The score increases whenever the player successfully passes through a pipe pair.

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Python Programming
- Pygame Development
- Event-Driven Programming
- Collision Detection Algorithms
- Game Physics
- Asset Management
- Debugging and Problem Solving
- Git and GitHub Workflow

---

## Challenges Faced

### Collision Accuracy

Designing a reliable collision system while maintaining smooth gameplay.

### Pipe Generation Logic

Creating randomized yet playable pipe placements.

### Physics Tuning

Balancing gravity and flap strength to provide an enjoyable user experience.

---

## Future Improvements

- High Score System
- Local Leaderboard
- Game Over Screen
- Difficulty Levels
- Animated Bird Sprites
- Pause and Resume Feature
- Power-Ups and Bonuses
- Mobile Compatibility
- Database Integration

---

## Author

**Shreyas Goyal**

B.Tech Computer Science Engineering (AI & ML)

### Areas of Interest

- Python Development
- Artificial Intelligence & Machine Learning
- Full Stack Web Development
- Open Source Development
- Data Structures & Algorithms

### Connect With Me

- **GitHub:** https://github.com/shreyas2007-goyal
- **LinkedIn:** https://www.linkedin.com/in/shreyas-goyalofficial/
- **Portfolio:** IN Progress

---

## License

This project is developed for educational and learning purposes.

Feel free to fork, modify, and enhance the project for personal use.