# Artificial-Intelligence


## 1. Pacman 

In this project, Pacman agent will find paths thoughout his maze world, both to reach a particular location and to collect food essentials. We used Python implementation of general search algorithms and applied them to Pacman scenarios. 


### A) Search Algortihms Used


| Algortihms | Application     | Description                |
| :-------- | :------- | :------------------------- |
| `depthFirstSearch` | `Done` | **Required**. Search the deepest nodes in the search tree first. |
| `breadthFirstSearch` | `Done` | **Required**. Search the shallowest nodes in the search tree first. |
| `uniformCostSearch` | `Done` | **Required**. Search the node of least total cost first. |
| `aStarSearch` | `Done` | **Required**. Search the node that has the lowest combined cost and heuristic first. |

### B) Running Tests For Search Algorithms 

To run tests, see `commands.txt`.

Example:

To play a game of Pacman type the following command line: 

```bash
  python pacman.py 
```

Test Run for DFS - Tiny Maze

```bash
  python pacman.py -l tinyMaze -p SearchAgent
```
![DFS - Tiny Maze Screenshot](Pacman/Screenshots/Tiny%20Maze%20-%20DFS.png)

Test Run for BFS - Medium Maze

```bash
  python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5
```
![BFS - Big Maze Screenshot](Pacman/Screenshots/Big%20Maze%20-%20BFS.png)

Test Run for UCS - Medium Scary Maze

```bash
  python pacman.py -l mediumScaryMaze -p StayWestSearchAgent
```
![UCS - Medium Scary Maze Screenshot](Pacman/Screenshots/Medium%20Scary%20Maze%20-%20UCS.png)
