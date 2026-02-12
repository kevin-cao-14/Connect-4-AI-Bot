#Overview
This project implements an adversarial game-playing agent for Connect 4 using a depth-limited minimax search with alpha-beta pruning. The agent evaluates board states and selects moves that maximize win probability while preventing opponent threats.

Key Components:
- Game state representation and legal move generation
- Heuristic board evaluation (win/block/double-threat detection)
- Minimax decision search with alpha-beta pruning optimization
- Turn-based simulation for agent vs. human gameplay


How to Run
rmarkdown::render("connect4.Rmd")
