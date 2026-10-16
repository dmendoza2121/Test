# Brick Breaker

A dependency-free browser brick breaker game (HTML5 canvas + vanilla JS), all in one file.

## Play

Open `index.html` in a browser — no build step, server, or other files required.
It works on phones and tablets too: the playfield adapts to portrait or
landscape, and you can add the page to your home screen to play full screen.

## Controls

- **Move:** ← / → or A / D, or the mouse
- **Launch / continue:** Space, Enter, or click
- **Pause:** P, Esc, or the pause button

On a touchscreen, drag anywhere on the playfield to move the paddle (your
finger never has to cover it) and tap to launch. Use the on-screen button to
pause; the game also pauses itself when you switch apps.

## Features

- 4 level layouts that repeat once at higher difficulty (8 levels total), with multi-hit and unbreakable bricks
- Paddle hit position controls the bounce angle
- Power-ups: **W** wide paddle, **M** multi-ball, **S** slow ball, **♥** extra life
- Score, lives, and a best score saved in localStorage
