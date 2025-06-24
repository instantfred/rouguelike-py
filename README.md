# rouguelike-py

A simple roguelike game developed in Python, following a tutorial-style progression.

## About

This project is a hands-on implementation of a classic roguelike game. It's built using Python and the `tcod` library. The goal is to build a feature-complete roguelike from the ground up, learning about game loops, entity management, procedural generation, and more.

## Current Features

*   **Turn-based Movement:** Move your character (`@`) around the map.
*   **Procedural Dungeon Generation:** Every new game creates a unique dungeon with rooms and connecting tunnels.
*   **NPCs:** The dungeon is populated with enemies (like orcs `o`).
*   **Field of View (FOV):** The map is revealed as you explore. Areas outside your line of sight are shrouded in a "fog of war".
*   **Collision Detection:** You can't walk through walls or other entities.

## Screenshot

A typical view of the game running in a terminal:

![Roguelike tutorial](https://github.com/user-attachments/assets/5e28a9e5-5221-4676-9f9f-baa0e50ca507)


## Getting Started

### Prerequisites

*   Python 3.8+
*   The dependencies listed in `requirements.txt`.

### Installation & Running

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/instantfred/rouguelike-py.git
    cd rouguelike-py
    ```

2.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the game:**
    ```bash
    python main.py
    ```

## Controls

*   **Arrow Keys** or **WASD**: Move the player character (`@`).
*   **Escape**: Exit the game.
