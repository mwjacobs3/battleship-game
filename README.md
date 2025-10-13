# Battleship Game 🚢

A fully functional, browser-based Battleship game with an intelligent AI opponent. Built as a technical demonstration for understanding developer workflows and AI-assisted coding tools.

## 🎮 [Play the Game Live](https://mwjacobs3.github.io/battleship-game/)

## 📋 Project Links
- **Live Game**: https://mwjacobs3.github.io/battleship-game/
- **Bug Documentation**: [BUG_DOCUMENTATION.md](BUG_DOCUMENTATION.md)
- **GitHub Repository**: https://github.com/mwjacobs3/battleship-game

## Features
- ⚓ Interactive ship placement with horizontal/vertical orientation
- 🎯 Smart AI opponent with hunt-and-target strategy  
- 💥 Visual feedback for hits, misses, and sunk ships
- 📱 Responsive design with Tailwind CSS
- 🎨 Clean, intuitive user interface
- ♻️ Complete game reset functionality

## Technologies Used
- **React 18** - UI framework
- **Tailwind CSS** - Styling
- **Vanilla JavaScript** - Game logic
- **No build tools required** - Runs directly in browser

## How to Play

### Setup Phase
1. Place all 5 ships on your board by clicking cells
2. Toggle between horizontal (→) and vertical (↓) orientation
3. Ships: Carrier (5), Battleship (4), Cruiser (3), Submarine (3), Destroyer (2)

### Attack Phase
1. Click cells on the AI board to fire
2. Red cells with target icon = Hit 💥
3. Blue cells with dot = Miss 💧
4. Sink all enemy ships to win!

## AI Strategy
The AI uses a sophisticated two-mode approach:
- **Hunt Mode**: Strategic random placement until finding a target
- **Target Mode**: Intelligent adjacent cell targeting after scoring a hit
- **Adaptive Behavior**: Determines ship orientation and continues along the axis

## Development Process

This project was built using AI-assisted development tools to gain hands-on experience with:
- Modern developer workflows
- Debugging complex state management issues
- React hooks and component lifecycle
- Game logic and AI algorithms

### Initial Development (Windsurf/Claude)
The game was initially developed with AI assistance, identifying and fixing 9 critical bugs related to state management, game logic, and UI interactions.

### October 2025 Code Review (Devin)
A comprehensive code review session identified and fixed 3 additional bugs:
- **Bug #10**: Shallow copy mutation in AI targeting mode (High severity)
- **Bug #11**: Silent AI ship placement failures (Medium severity)  
- **Bug #12**: Unused direction field in state (Code quality)

See [BUG_DOCUMENTATION.md](BUG_DOCUMENTATION.md) for detailed notes on all 12 bugs identified and resolved, including root causes, fixes applied, and prevention strategies.

## Running Locally

**No installation required!**

1. Clone this repository:
```bash
   git clone https://github.com/mwjacobs3/battleship-game.git
