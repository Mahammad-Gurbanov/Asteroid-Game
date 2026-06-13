# Asteroid Game
This is a single player asteroid game, which is one of projects in Boot.dev
backend developer path. This game was coded in pygame using OOP principles. 
I really enjoyed this project, and I am looking forward to making more game
projects in the future.

## Running
```bash
  # 1. Install uv (if you don't have it yet)
  curl -LsSf https://astral.sh/uv/install.sh | sh

  # 2. Clone the repository
  git clone https://github.com/Mahammad-Gurbanov/Asteroid-Game.git
  cd asteroids-game

    # 3. Create virtual environment and install dependencies
  uv sync

  # 4. (Optional) Activate the environment
  source .venv/bin/activate
```
## How to Play

**Objective**: Destroy as many asteroids as possible while surviving as long as you can.

### Gameplay
- Asteroids float across the screen in different sizes.
- Shooting an asteroid **splits** it into two smaller asteroids.
- Only the **smallest asteroids** are completely destroyed when hit.
- Avoid touching any asteroids — if your ship collides with one, the game is over.
- Survive longer and destroy more asteroids to achieve a higher score.

**Controls**:
- WASD — Rotate and thrust
- Space — Shoot