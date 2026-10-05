# 🇮🇳 India Road Network – Dijkstra's Shortest Path Algorithm

## Project Overview
This project implements Dijkstra's Shortest Path Algorithm (Uniform Cost Search for a weighted graph) to find a minimum-distance route between cities in an Indian road network.

## Objectives
- Represent Indian cities as graph nodes.
- Represent roads as weighted edges.
- Find the shortest route between a source and destination.
- Calculate total route distance.
- Visualize the road network and selected route.

## Technologies
- Python
- Google Colab
- Pandas
- NumPy
- NetworkX
- Matplotlib

## Methodology
1. Load or define city and road-distance data.
2. Build a weighted graph.
3. Select source and destination cities.
4. Apply Dijkstra's algorithm.
5. Reconstruct the shortest path.
6. Calculate total distance.
7. Visualize the network and shortest route.

## Algorithm
Dijkstra repeatedly selects the unvisited node with the smallest known distance and relaxes its neighboring edges.

For a priority-queue implementation:

**Time Complexity:** O((V + E) log V)

where V is the number of cities and E is the number of roads.

## Output
The notebook displays:
- Source city
- Destination city
- Shortest route
- Total distance
- Graph visualization

## Applications
- GPS navigation
- Route planning
- Logistics
- Transportation networks
- Emergency routing

## Limitations
The basic implementation uses a static road network and does not account for real-time traffic, road closures, or changing travel conditions.

## Conclusion
The project demonstrates how a real-world Indian road network can be modeled as a weighted graph and solved using Dijkstra's shortest-path algorithm.

## How to Run
1. Open the notebook in Google Colab.
2. Upload the required dataset if applicable.
3. Run cells from top to bottom.
4. Select the source and destination.
5. View the shortest path, distance, and visualization.
