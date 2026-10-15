# Star Pusher (Web Edition)

A Sokoban-style puzzle game built with Python and Pygame-CE. Push stars onto the goal markers to clear each level.

Playable locally and in modern web browsers via WebAssembly ([Pygbag](https://pygame-web.github.io/)).

## How to Run Locally

### Prerequisites
- Python 3.10+
- `pip install pygame-ce pygbag`

### Play Locally
```bash
python main.py
```

### Run in Browser Locally
```bash
python -m pygbag main.py
```
Open `http://localhost:8000` in your web browser.

## Controls
- **Arrow Keys**: Move player and push stars
- **WASD**: Pan camera view
- **P**: Change character skin
- **Backspace**: Reset current level
- **N / B**: Next / Previous level
- **Escape**: Quit game
