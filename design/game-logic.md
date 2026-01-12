# Game Logic Design

The core game logic is implemented independently of the UI to ensure deterministic behavior across gameplay modes.

## Responsibilities

- Maintain board state
- Enforce turn order
- Validate moves
- Detect win, loss, or draw conditions

## Turn Management

A centralized turn controller alternates turns between players or invokes the AI engine when required.

## Win & Draw Detection

The board is evaluated after each move using predefined winning patterns.  
Draws are detected when all cells are filled without a winning configuration.

