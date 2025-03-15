# Tic Tac Toe React Game

A classic Tic Tac Toe game built with React, demonstrating modern JavaScript techniques, component-based architecture, and state management using hooks. This project is an excellent example of applying functional programming principles and event-driven UI development in a simple, interactive game.

## Project Overview

This project implements a two-player Tic Tac Toe game where players take turns selecting squares on a 3x3 grid. The game logic checks for winning combinations or a draw, and provides a rematch option upon game completion. Key React concepts such as hooks, state management, and component composition are utilized to build an engaging user interface.

## Technical Features

- **React Functional Components:**  
  The application is built entirely with React functional components, ensuring modularity and reusability.  
  [Learn more about React components](https://reactjs.org/docs/components-and-props.html) (&#8203;:contentReference[oaicite:0]{index=0}).

- **State Management with Hooks:**  
  The `useState` hook is used to manage game state, including turns, active players, and UI state for editing player names.  
  [Explore React Hooks](https://reactjs.org/docs/hooks-intro.html) (&#8203;:contentReference[oaicite:1]{index=1}).

- **Component-Based Architecture:**  
  The UI is split into distinct components such as:
  - `Header` – Displays the game logo and title.
  - `Player` – Manages player information and supports inline editing.
  - `GameBoard` – Renders the grid and handles square selection.
  - `Log` – Keeps a history of moves.
  - `GameOver` – Displays game results and provides a rematch option.

- **Game Logic Implementation:**  
  The game logic is encapsulated within the main `App` component, where it:
  - Determines the active player.
  - Records and updates moves.
  - Checks for win conditions using predefined winning combinations.
  - Identifies a draw situation.

- **Event Handling and Conditional Rendering:**  
  User interactions (such as clicking squares, editing names, or starting a rematch) are managed with event handlers and conditional rendering to update the UI dynamically.

## Skills Applied

- **Modern JavaScript (ES6+):**  
  Use of arrow functions, destructuring, and spread operators to write clean, concise code.  
  [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript) (&#8203;:contentReference[oaicite:2]{index=2}).

- **Functional Programming:**  
  Functional patterns are applied (e.g., pure functions for state derivation and immutability in state updates).

- **UI/UX Development:**  
  Implementing an interactive game UI with real-time feedback, inline editing, and a log for game history.

- **Component Communication:**  
  Effective use of props to share data and event handlers between parent and child components.

## Project Structure

```plaintext
├── src
│   ├── components
│   │   ├── Header.js          // Renders the game header with logo and title
│   │   ├── Player.js          // Manages player state and allows name editing
│   │   ├── GameBoard.js       // Displays the Tic Tac Toe grid and handles moves
│   │   ├── Log.js             // Logs each move made during the game
│   │   └── GameOver.js        // Displays game results and offers a rematch option
│   ├── winning-combinations.js // Contains logic for determining winning moves
│   └── App.js               // Main component orchestrating game state and logic
└── package.json
