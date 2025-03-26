# Ejercicio 2: Resolución de un Laberinto con Caminos de Longitud Mínima

## Descripción del Problema
En este ejercicio, se presenta un laberinto representado como una matriz cuadrada, donde cada posición contiene un valor natural y cuatro valores booleanos. Estos valores indican si es posible moverse en las direcciones norte, este, sur y oeste desde esa casilla. El objetivo es encontrar un camino de longitud mínima entre dos casillas dadas, donde la longitud del camino se define como la suma de los valores naturales de las casillas por las que se pasa.

## Enfoque
- El laberinto se modela como una estructura orientada a objetos, donde cada casilla contiene un valor natural y los posibles movimientos (norte, sur, este, oeste).
- Se aplica un algoritmo de búsqueda en grafos, como Dijkstra o A*, para encontrar el camino mínimo basado en la suma de los valores de las casillas.
- La solución garantiza el camino más corto al optimizar el proceso de recorrido.

## Características de la Solución:
- **Diseño Orientado a Objetos**: El laberinto se representa como una matriz de objetos, cada uno con un valor natural y valores booleanos para las direcciones de movimiento.
- **Algoritmos de Búsqueda en Grafos**: Se utilizan algoritmos como Dijkstra o A* para la búsqueda eficiente del camino en un grafo ponderado.
- **Optimización**: El algoritmo minimiza la longitud del camino calculando la suma de los valores de las casillas recorridas.

## Aplicaciones
Este enfoque es aplicable a problemas reales en campos como inteligencia artificial, robótica, navegación autónoma y optimización de sistemas de rutas.

-------------------------------------------------------------------------------------------------------------

# Exercise 2: Solving a Maze with Minimum Path Length

## Problem Description
This exercise involves solving a maze represented as a square matrix, where each position contains a natural value and four boolean values. These boolean values indicate whether it is possible to move in the directions of north, east, south, and west from that cell. The goal is to find the minimum path between two given cells, where the path length is the sum of the natural values of the cells traversed.

## Approach
- The maze is modeled as an object-oriented structure, where each cell contains a natural value and the possible movement directions (north, south, east, west).
- A graph search algorithm, such as Dijkstra's or A*, is applied to find the minimum path based on the sum of the values in the cells.
- The solution ensures the shortest possible path by optimizing the traversal process.

## Solution Features:
- **Object-Oriented Design**: The maze is represented by a matrix of objects, each with a natural value and boolean values for movement direction.
- **Graph Search Algorithms**: Algorithms like Dijkstra’s or A* are used for efficient pathfinding in a weighted graph.
- **Optimization**: The algorithm minimizes the path length by calculating the sum of the values of the cells traversed.

## Applications
This approach is applicable to real-world problems in fields like artificial intelligence, robotics, autonomous navigation, and optimization of routing systems.



