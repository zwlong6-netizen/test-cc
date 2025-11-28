# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple web-based Snake game project with a single HTML file containing the complete game implementation using HTML5 Canvas and JavaScript.

## Project Structure

- `snake-game.html` - Self-contained Snake game with embedded HTML, CSS, and JavaScript
- `.gitignore` - Java-focused gitignore configuration (appears to be template-based)
- `LICENSE` - Project license file
- `README.md` - Minimal project readme

## Architecture

The game is implemented as a single-page application with:

- **Canvas-based rendering**: 400x400px game board using HTML5 Canvas API
- **Game state management**: JavaScript variables tracking snake position, food, score, and game status
- **Event handling**: Keyboard controls for movement (arrow keys) and pause (spacebar)
- **Local storage**: High score persistence using browser localStorage
- **Responsive design**: CSS with flexbox layout and gradient backgrounds

## Game Mechanics

- Grid-based movement system (20px grid, 20x20 tiles)
- Collision detection for walls and self-collision
- Score tracking with persistent high score
- Pause/resume functionality
- Game over screen with restart capability

## Running the Project

Simply open `snake-game.html` in any modern web browser. No build process, dependencies, or server setup required.

## Development Notes

- No external dependencies or frameworks
- Pure JavaScript (ES6+ features not used)
- CSS uses modern features (flexbox, backdrop-filter, gradients)
- Game loop runs at 150ms intervals via setInterval
- All game logic is contained within <script> tags in the HTML file

## Git Repository

Remote: https://github.com/zwlong6-netizen/test-cc.git
Main branch: main