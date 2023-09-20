# AI ChessBot

This project implements a chess-playing AI using a JavaScript-based algorithm that employs Alpha-Beta Pruning for improved efficiency during search and utilizes Piece-Square Tables for board evaluation. The AI also offers five difficulty levels set out by level searching. Additionally, it includes an HTML and CSS GUI to interact with the AI and play chess.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Algorithm Overview](#algorithm-overview)
- [Difficulty Levels](#difficulty-levels)
- [File Structure](#file-structure)
- [Acknowledgements](#acknowledgements)

## Features

- Chess AI using Alpha-Beta Pruning.
- Board evaluation using Piece-Square Tables.
- HTML and CSS GUI for playing chess against the AI.
- Five difficulty levels based on search depth.

## Prerequisites

- A modern web browser that supports HTML5 and CSS3.
- Basic understanding of chess rules and gameplay.

## Usage

1. Clone the repository to your local machine:

```
git clone https://github.com/jimmyvdw/AI_ChessBot/
cd chess-ai
```

2. Open `index.html` in a web browser:

```
# Double-click on index.html
```

3. Play chess against the AI using the GUI and select a difficulty level.

## Algorithm Overview

The AI utilizes the Alpha-Beta Pruning algorithm, an extension of the minimax algorithm, for efficient move decision making. Alpha-Beta Pruning reduces the number of nodes evaluated in the minimax tree by disregarding branches that are guaranteed to be worse than previously evaluated branches.

Piece-Square Tables are used for board evaluation. These tables assign a value to each piece on the board based on its position. The AI calculates the overall board evaluation by summing the values of the pieces based on their positions.

## Difficulty Levels

The AI offers five difficulty levels based on the search depth of the algorithm. The search depth determines how many moves ahead the AI will consider for each move. Higher difficulty levels correspond to deeper search and more complex gameplay.

- **Level 1:** Shallow search - Beginner (2 moves ahead)
- **Level 2:** Moderate search - Easy (3 moves ahead)
- **Level 3:** Intermediate search - Normal (4 moves ahead)
- **Level 4:** Advanced search - Hard (5 moves ahead)
- **Level 5:** Expert search - Extreme (6 moves ahead)

## File Structure

```
/
|-- index.html                 # HTML file for the GUI
|-- style.css                  # CSS file for styling the GUI
|-- script.js                  # JavaScript file containing the AI algorithm, board logic, and difficulty levels
|-- ...
```
