# Artificial Intelligence: Unit 1

---

The goal of the project is to implement search algorithms and to find the optimal path in an $N\times N$ labyrinth.

## Project Overview

This repository contains a project divided into several parts, where different search algorithms are implemented and experimented with. In particular:

- **Part 1-3:** Implementations of various search algorithms.
- **Part 4:** A special scenario where a ghost 👻 pursues you using its own A* algorithm. To avoid the ghost, the AB algorithm is implemented. You are required to complete the moves for the minimizing_player based on the corresponding moves of the maximizing_player. Additionally, a heuristic function that factors in the distance from both the goal and the ghost must be defined.

## Experimental Results

Experiments compare the performance of:
- **Dijkstra's Algorithm:** Always finds the optimal path.
- **A\* Algorithm:** Finds the optimal path if the heuristic is admissible.
- **Best-First Algorithm:** Generally expands fewer nodes but may not find the optimal path.

Results are documented through descriptive gifs and execution time measurements. The evaluation also covers:
- The correctness of each algorithm.
- The number of expanded nodes and how they scale as the labyrinth's size increases.
- The influence of heuristics on the overall performance.
