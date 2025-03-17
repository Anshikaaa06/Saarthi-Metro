# Saarthi-Metro
Develop a C++ program for the Delhi Metro Application (Saarthi Mtero), which takes input from the user regarding the source and destination stations on the Delhi Metro, and provides information about the shortest metro route between these two stations, along with the fare. The idea will be implemented using Graph and Heap data structures. The graph will be having nodes and edges. Nodes represent a metro station that will be containing certain information regarding that station like it's name, it's metro corridor, and the lines which it connects. Edges (the connection between two nodes) represent the distance between the two stations and the cost of each edge will be equal to the distance between the two of its connecting stations(nodes). The program uses graph and heap data structures to represent and calculate the metro routes and fares efficiently, primarily relying on the Dijkstra algorithm. Some Standard Template Library (STL) is used during development like vector,unordered_map,priority_queue,stack,etc.  
# Algorithm Steps:  
1. **Graph Representation of Delhi Metro**: Implement a Graph data structure in C++ where each node represents a metro station. Every station should store details such as its name, the metro corridor it belongs to, and the lines it interconnects. The edges between stations will indicate connectivity, with their weights corresponding to the distance between them.

2. **Heap for Efficient Processing**: Utilize a Heap data structure (e.g., unordered_map) in C++ to effectively manage station nodes during the execution of Dijkstra’s algorithm for shortest path computation.

3. **User Input Handling**: Prompt users to enter the names of their starting and destination metro stations, ensuring flexibility in route selection.

4. **Shortest Path Calculation**: Implement Dijkstra’s algorithm in C++ to determine the shortest possible metro route between the chosen stations, considering distances as edge weights.

5. **Fare Estimation**: Compute the travel fare for the identified shortest route based on the total distance covered, following a predefined fare system similar to the Delhi Metro pricing model.

6. **Route Visualization**: Display the optimal metro path, listing all the stations a commuter needs to travel through from the source to the destination.

7. **Total Fare Display**: Clearly present the final fare cost for the journey, making it easy for users to understand their travel expenses.

8. **Metro Map Integration**: Incorporate a metro network visualization within the C++ program to assist commuters in navigating and comprehending the metro layout effectively.

9. **Cross-Platform Compatibility**: Ensure that the C++ application functions smoothly across various popular IDEs, such as Visual Studio, Code::Blocks, and others, making it accessible even to those with basic C++ knowledge.
