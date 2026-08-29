# Flappy Bird

A modern implementation of the classic Flappy Bird game, built with React and Vite. This project demonstrates game development principles using modern web technologies with a fast development experience.

## Project Overview

**Flappy Bird** is an interactive browser-based game where players control a bird to navigate through obstacles. The game combines simple yet challenging mechanics with smooth animations and real-time gameplay.

## Purpose

This project serves as a practical learning tool for:
- Building interactive games with React
- Implementing game physics and collision detection
- Managing game state and lifecycle
- Creating responsive and performant web applications
- Exploring modern front-end development with Vite

## Technologies Used

- **React** - UI component framework for building interactive game interface
- **Vite** - Next-generation build tool for lightning-fast development
- **JavaScript/JSX** - Game logic and component implementation
- **CSS** - Game styling and animations
- **ESLint** - Code quality and consistency

## Features

- Classic Flappy Bird gameplay mechanics
- Responsive design for various screen sizes
- Smooth animations and visual feedback
- Score tracking and game statistics
- Simple and intuitive controls

## Getting Started

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

The application will start at `http://localhost:5173` with Hot Module Replacement (HMR) enabled.

### Build

```bash
npm run build
```

Creates an optimized production build in the `dist` directory.

### Preview

```bash
npm run preview
```

## Project Structure

```
src/
  ├── App.jsx          # Main game component
  ├── App.css          # Application styles
  ├── main.jsx         # Entry point
  ├── index.css        # Global styles
  └── assets/          # Game assets
public/                # Static files
```

## How to Play

- Click or press Space to make the bird flap
- Navigate through the obstacles without colliding
- Score increases as you successfully pass through gaps
- Game ends on collision with obstacles or boundaries

## Development with GitHub Copilot

This project was developed with the assistance of **GitHub Copilot**, an AI-powered code assistant. Copilot was instrumental in:

- **Code Generation** - Automatically generating React component boilerplate and game logic
- **Game Physics** - Providing collision detection algorithms and physics calculations
- **State Management** - Assisting with React hooks and game state management patterns
- **Debugging** - Identifying issues and suggesting fixes for game behavior
- **Documentation** - Generating comments and documentation for code clarity
- **Best Practices** - Following modern React and Vite development patterns
- **Optimization** - Improving performance and code efficiency

This project demonstrates how AI-assisted development can accelerate learning and game development workflows while maintaining code quality and best practices.

## Development Notes

This project uses Vite's plugin system with optimized React support for best development and build performance. The development experience was enhanced using GitHub Copilot for faster iteration and learning.
