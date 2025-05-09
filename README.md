# ♟️ Human vs AI Chess Game

A Python-based chess game where a human player competes against an AI opponent powered by the **Minimax algorithm with Alpha-Beta Pruning**. The game features a clean **Pygame GUI**, full chess logic, and real-time interaction.

## 📌 Features

- ✅ Full chess rules (castling, en passant, pawn promotion, check/checkmate/stalemate)
- ♟️ Human vs AI gameplay with alternating turns
- 🧠 AI opponent using Minimax with Alpha-Beta Pruning
- 🖱️ Interactive GUI built with Pygame
- 🕹️ Click-based piece selection and movement
- 📜 Move history panel showing the last 10 moves

## 🧠 AI Logic

- Implements **Minimax with Alpha-Beta Pruning**
- Evaluates moves based on **piece values and board state**
- Selects the move that **maximizes its chances of winning**

## 🏗️ Code Structure

- `Piece Classes` – Individual movement logic for King, Queen, Rook, Bishop, Knight, Pawn
- `Move Class` – Encapsulates move details including castling, en passant, promotion
- `Board Class` – Manages board state, move validation, and endgame conditions
- `Player Classes` – HumanPlayer (input via GUI) and AIPlayer (decision via Minimax)
- `ChessGame Class` – Manages game flow and state updates

## 🖼️ GUI Overview

- Built using **Pygame**
- Loads chess piece sprites from an `assets/` folder
- Allows intuitive drag-and-drop style piece movement
- Displays move history on a side panel

## 🚀 Getting Started

### Prerequisites
- Python 
- `pygame` library

### Installation
```bash
pip install pygame
