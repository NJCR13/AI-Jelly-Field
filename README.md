# IA-Jelly-Field-Puzzle

A Python project that implements the classic Jelly Field puzzle game and integrates search algorithms to automatically solve game states.

## Project Overview

This project was developed using Python and Pygame to recreate the Jelly Field game. Beyond the interactive gameplay, the focus was on applying artificial intelligence search algorithms to find optimal or near-optimal solutions for given puzzles.

##  Features  
- **Playable Game:** Built with Pygame, allowing manual play of Jelly Field levels.  
- **Search Algorithm Integration:** Implemented and compared multiple algorithms to solve the puzzles:  
  - **Breadth-First Search (BFS)**  
  - **Depth-First Search (DFS)**  
  - **Greedy Best-First Search**  
  - **A\*** Search (with heuristics)  
- **Visualization:** Real-time display of algorithm solving steps on the game board.  
- **Performance Comparison:** Evaluation of algorithms in terms of speed, efficiency, and solution optimality.  

## Tech Stack  
- **Language:** Python  
- **Frameworks/Libraries:** Pygame, standard Python libraries  

## Group

- Alexandre Morais
- Carlos Costa
- Nuno Ramos

### How to run


```
pip install pygame
```

```
python -m venv venv

python3 -m venv venv
```

Windows
```
venv/Scripts/activate
```

Linux
```
source venv/bin/activate
```

```
python game.py

python3 game.py
```
