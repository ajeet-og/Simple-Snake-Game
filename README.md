🐍 Snake Game (Python + Curses)

A simple terminal-based Snake Game written in Python using the curses library. Control the snake with your keyboard, eat food to grow longer, and avoid hitting the walls or yourself.

📌 Features

Runs directly in the terminal

Keyboard-controlled snake movement

Random food generation

Collision detection (walls & self)

Minimal and lightweight

🛠 Requirements

Python 3.x

curses module

For Linux / macOS

curses comes preinstalled with Python.

For Windows

Install the Windows-compatible version:

pip install windows-curses

▶️ How to Run

Clone the repository:

git clone https://github.com/your-username/snake-game-curses.git
cd snake-game-curses


Run the game:

python snake.py

🎮 Controls
Key	Action
⬆️ Arrow Up	Move Up
⬇️ Arrow Down	Move Down
⬅️ Arrow Left	Move Left
➡️ Arrow Right	Move Right
❌ Game Over Conditions

Snake hits the wall

Snake collides with itself

📂 File Structure
snake-game/
│
├── snake.py      # Main game file
└── README.md     # Project documentation

⚠️ Notes

The game runs inside the terminal window—do not resize the terminal while playing.

Best experienced in a full-screen terminal.

Uses curses.ACS_CKBOARD for snake body and curses.ACS_PI for food.

📜 License

This project is open-source and free to use for learning and personal projects.

⭐ Acknowledgements

Inspired by classic Snake games and built using Python’s curses library.
