# Snake Game

A classic Snake game built with HTML5 Canvas and vanilla JavaScript — no build tools or dependencies required.

## How to run in a browser

### Option 1 — Open directly (simplest)

1. Download or clone this repository.
2. Double-click `index.html`, or right-click it and choose **Open with → your browser**.

The file opens straight in any modern browser (Chrome, Firefox, Edge, Safari).

### Option 2 — Via a local web server (recommended)

Some browsers restrict local file access. If the game doesn't load with Option 1, serve it with a simple local server:

**Python 3**
```bash
python3 -m http.server 8000
```
Then open <http://localhost:8000> in your browser.

**Node.js (npx)**
```bash
npx serve .
```
Then open the URL shown in your terminal.

**VS Code**
Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension, right-click `index.html`, and select **Open with Live Server**.

## Controls

| Key | Action |
|-----|--------|
| Arrow keys or WASD | Move the snake |
| P | Pause / Resume |

## Gameplay

- Eat the red food to grow and earn **+10 points**.
- Avoid hitting the walls or running into yourself.
- Your **high score** is saved in the browser automatically.
