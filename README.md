# dfs-maze-generator

### Objective
1. Create bi-directional graph for a blank n-by-n array
2. Use depth-first-search to create a maze graph
3. Use depth-first-search to solve the maze

### Methods

dfs search of graph object. Graph made with defaultdict.

Packages used:
- collections
- matplotlib
- time
- numpy

### Results
On a Surface Book. Windows 10. i7-6600 CPU@ 2.6GHz.
>python dfs_maze_plots.py

Maze size: 40x40

Creating graph:
Graph vertex num: 1600
Graph edge num: 6240
Created in: 0.372 s.

![](https://github.com/donnie-jun/dfs-maze-generator/blob/master/maze_raw.png)


Solving graph:
Graph vertex num: 742
Graph edge num: 1482
Found a path in 831 steps.
Solved in: 0.150 s.

![](https://github.com/donnie-jun/dfs-maze-generator/blob/master/maze_solved.png)


Total time: 0.522 s.

>python dfs_maze_timetestonly.py

Maze size: 40x40

Creating graph:
Graph vertex num: 1600
Graph edge num: 6240
Created in: 0.136 s.

Solving graph:
Graph vertex num: 725
Graph edge num: 1448
Found a path in 969 steps.
Solved in: 0.023 s.

Total time: 0.159 s.

