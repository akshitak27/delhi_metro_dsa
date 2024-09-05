Delhi Metro Route and Fare Calculator

Overview

The Delhi Metro Route and Fare Calculator is a Java-based application designed to help commuters navigate the Delhi Metro system efficiently. The program allows users to input the names of the source and destination metro stations, and it calculates the shortest route along with the fare based on the distance between the two stations.

This application utilizes graph theory and heap data structures to compute the shortest path between stations. The metro network is represented as a graph where nodes represent metro stations, and edges represent the connections between them, with weights corresponding to the distance.

Features
Graph Representation: Models the Delhi Metro network using a graph where nodes represent stations and edges represent connections with distances.
Shortest Path Calculation: Implements algorithms such as Dijkstra's Algorithm, Breadth-First Search (BFS), and Depth-First Search (DFS) to find the shortest route between two stations.
Fare Calculation: Computes the fare based on the total distance of the shortest path between the source and destination stations.
Metro Map: Provides a visualization of the metro network to aid in route navigation.

Project Structure
Graph_M.java: Contains the core implementation of the graph, including node and edge definitions, as well as the algorithms for calculating shortest paths and fares.
Heap.java: Implements a heap data structure used for efficiently managing the priority queue in Dijkstra's Algorithm.

How It Works
Input: The user is prompted to enter the names of the source and destination metro stations.
Graph Construction: The metro network is represented as a graph with nodes (stations) and edges (connections).
Pathfinding: The application uses graph algorithms to compute the shortest path between the given stations.
Dijkstra's Algorithm: Finds the shortest path from the source to the destination.
Breadth-First Search (BFS): Explores the graph level by level.
Depth-First Search (DFS): Explores the graph by going as deep as possible along each branch.
Fare Calculation: The fare is calculated based on the distance of the shortest path.
Output: Displays the shortest route and the fare to the user.

Prerequisites
Java Development Kit (JDK) 8 or higher
A Java IDE or text editor (e.g., IntelliJ IDEA, Eclipse, VS Code)
