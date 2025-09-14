# Pentago — Minimax Game AI

_Intro to Artificial Intelligence — University of Tehran_

This project implements an **AI agent** for the two-player strategy game **Pentago**, using the **Minimax algorithm** with an optional **Alpha–Beta pruning** optimization.  
The AI evaluates board states, explores possible moves, and selects the optimal strategy to maximize its winning chances.


## Tasks

1.  **Game Modeling**
    -   Represent the Pentago board as a 6×6 grid, divided into four 3×3 quadrants.
    -   Define rules:
        -   Players alternate placing a stone (black or white).
        -   After each placement, a quadrant is rotated 90° (clockwise or counterclockwise).
        -   The goal is to align **five consecutive stones**.
            
2.  **Minimax Algorithm**
    
    -   Implement recursive search to evaluate possible moves.
    -   Design a **heuristic evaluation function** for non-terminal board states.
    -   Extend with **Alpha–Beta pruning** to reduce explored nodes.
        
3.  **Testing & Evaluation**
    
    -   Run games at different search depths.
    -   Compare performance (runtime, explored nodes, win rates) with and without pruning.
    -   Play against a random-move opponent and analyze results.
        

## License

This project is licensed under the **MIT License**.


## Acknowledgements

Developed under the supervision of **Dr. Fadaei** and **Dr. Yaghoubzadeh**  
Designed by **Kourosh Sajadi, Shahriar Attar, Farbod Azim Mohseni**
