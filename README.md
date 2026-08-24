# BFS and DFS Algorithms - AI Project 🤖🕸️

## Overview
This project explores and implements graph traversal algorithms, specifically **Breadth-First Search (BFS)** and **Depth-First Search (DFS)**, which are fundamental concepts in Artificial Intelligence for problem-solving, pathfinding, and exploring networks[span_0](start_span)[span_0](end_span). The project was developed as part of the AI coursework at King Khalid University[span_1](start_span)[span_1](end_span).

## Algorithms Details
*   **Breadth-First Search (BFS):** Explores the graph level by level[span_2](start_span)[span_2](end_span). It is implemented using a **Queue** data structure following the First In, First Out (FIFO) principle[span_3](start_span)[span_3](end_span). It is ideal for finding the shortest path in unweighted graphs[span_4](start_span)[span_4](end_span).
*   **Depth-First Search (DFS):** Explores the graph by going as deep as possible along one path before backtracking[span_5](start_span)[span_5](end_span). It is implemented using a **Stack** data structure following the Last In, First Out (LIFO) principle[span_6](start_span)[span_6](end_span). It is highly useful in AI for tasks like game tree search[span_7](start_span)[span_7](end_span).

## Computational Complexity
*   **Time Complexity:** Both algorithms operate in **$O(V+E)$** time, where $V$ is the number of vertices and $E$ is the number of edges, as they visit every node and connection[span_8](start_span)[span_8](end_span).
*   **Space Complexity:** Both algorithms require **$O(V)$** space in the worst-case scenario to store nodes in the queue (BFS) or stack (DFS)[span_9](start_span)[span_9](end_span).

## Performance Analysis
The project includes a Python implementation to compare the performance of both algorithms on a randomly generated large graph consisting of 1,000 vertices and 5,000 edges[span_10](start_span)[span_10](end_span). 
*   **BFS Execution Time:** ~0.0128 seconds[span_11](start_span)[span_11](end_span).
*   **DFS Execution Time:** ~0.0023 seconds[span_12](start_span)[span_12](end_span).
*   **Conclusion:** DFS was approximately 5.5 times faster in this specific large, dense graph scenario, as it explores paths deeply without the memory overhead of storing all neighbor nodes simultaneously like BFS[span_13](start_span)[span_13](end_span).

## How to Run
The Python script `main.py` contains the implementation for both algorithms and can be executed directly to see the traversal paths on sample directed and undirected graphs, followed by the performance benchmark on the large graph[span_14](start_span)[span_14](end_span).

## Team Members
*   Waad Sultan[span_15](start_span)[span_15](end_span)
*   Rawan Ali Alshehri[span_16](start_span)[span_16](end_span)
*   Lama Mohammed Alshehri[span_17](start_span)[span_17](end_span)
*   Shaden Abdullah[span_18](start_span)[span_18](end_span)
