# Snake Game

A simple Snake game built with HTML, CSS, and JavaScript. Use the arrow keys to guide the snake, eat the red food, and try to beat your high score.

## How to play

- Use the **arrow keys** to change direction.
- Eat the red food to increase your score.
- Avoid hitting the walls or the snake’s body.
- Press **Enter** after game over to restart.

## Run the game

No installation is needed.

1. Open `index.html` in a web browser.
2. Use the arrow keys to play.

## Features

- Snake movement on a grid.
- Keyboard controls that prevent direct reversals.
- Collision detection for walls and the snake’s body.
- Score display and increasing game speed as the score rises.
- High score saved in the browser with `localStorage`.
- Restart after game over.

## Project files

- `index.html` — Game page, drawing, and JavaScript game logic.
- `style.css` — Additional page styles.

## Current limitations

- Food placement is random and may overlap the snake.
- Eating food currently adds an extra segment in addition to the segment gained by keeping the tail. This can make the snake grow by more than one segment per food.
