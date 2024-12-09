# Tetris Game

A classic Tetris game implemented using HTML, CSS, and JavaScript.

## Introduction

Tetris Game is a classic Tetris game that brings the nostalgic experience of the original Tetris to the web. The game is designed to be simple and effective, providing a fun and engaging gameplay experience.

## Features

- Classic Tetris gameplay
- Score and level tracking
- Next piece preview

## How to Play

- Use the left and right arrow keys to move the pieces.
- Use the down arrow key to drop the pieces faster.
- Use the `Q` key to rotate the pieces counterclockwise.
- Use the `W` key to rotate the pieces clockwise.
- Clear lines to score points and advance levels.
- The game speeds up as you progress through levels.

## Project Structure

- `index.html`: The main HTML file that contains the game structure.
- `style.css`: The CSS file that styles the game.
- `script.js`: The JavaScript file that contains the game logic.

## How Levels Work

- The game starts at level 1.
- The player advances to the next level after clearing 3 lines.
- Each new level increases the game speed by decreasing the drop interval of the pieces.
- The drop interval decreases by 50ms for each new level, with a minimum interval of 100ms for safety.
