---

## ۵. Othello-AI-Minimax-Expectimax

```markdown
# ♟️ Othello-AI-Minimax-Expectimax

A full implementation of the **Othello (Reversi)** board game in Python, featuring multiple sophisticated **Artificial Intelligence (AI)** agents.

---

## ✨ AI Algorithms & Game Features

* **Minimax & Alpha-Beta Pruning:** Core search algorithm optimized for reduced search space and increased depth.
* **Expectimax:** AI agent designed for non-deterministic environments or randomized opponents.
* **MCTS (Monte Carlo Tree Search):** Advanced probabilistic search agent for robust decision-making.
* **Evaluation Function:** Custom heuristic for board state evaluation, heavily weighting **Corners**, **Mobility**, and **Sides**.
* **GUI:** Built with **Pygame** for visual gameplay (Human vs. AI, AI vs. AI).

---

## 🛠️ Technologies Used

| Technology | Role |
| :--- | :--- |
| **Python 3.x** | Core language. |
| **Pygame** | Graphical User Interface (GUI) and visualization. |
| **Minimax / Expectimax** | AI search algorithms implementation. |
| **OOP Design** | Modular structure with `Board`, `Game`, and `Player` classes. |

---

## 🚀 Getting Started

### Prerequisites
* Python 3.x

### Installation

```bash
pip install pygame

git clone [https://github.com/YOUR_USERNAME/Othello-AI-Minimax-Expectimax.git](https://github.com/YOUR_USERNAME/Othello-AI-Minimax-Expectimax.git)
cd Othello-AI-Minimax-Expectimax

python main.py

📂 File Structure
File	Description
main.py	Pygame GUI setup, game loop, and mode selection menu.
game.py	Game mechanics, turn switching, and victory condition logic.
board.py	Othello board representation, valid move calculation, and scoring.
player.py	Defines different player agents (RandomPlayer, MinimaxPlayer, MCTSPlayer, etc.).
minimax.py	Minimax algorithm with Alpha-Beta Pruning and evaluation function.
expectimax.py	Expectimax algorithm and evaluation function.
