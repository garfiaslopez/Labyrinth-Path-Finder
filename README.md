# Labyrinth Path Finder

Find a path to exit the labyrinth. Using DFS algorithm to search the exit and saving the positions to construct a path.

## Maze values
* -1 => Origin
* -2 => Destiny
*  0  => Free
*  1  => Blocked

## How to run
```
dotnet run
```

## Example Input.txt matrix
```
1,1,1,1,1
1,1,0,0,1
1,1,0,1,1
1,1,0,1,1
-1,0,0,1,-2
1,1,0,1,0
1,1,0,1,0
1,0,0,0,0
```

## Example Output.txt
```
El camino para salir del laberinto es:
[5, 1]
[5, 2]
[5, 3]
[6, 3]
[7, 3]
[8, 3]
[8, 4]
[8, 5]
[7, 5]
[6, 5]
[5, 5]
------------MAPA:------------
X X X X X 
X X X X X 
X X X X X 
X X X X X 
I O O X F 
X X O X O 
X X O X O 
X X O O O 

```