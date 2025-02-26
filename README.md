# Computer_Network_Project
A virtual network simulator that allows users to design, analyze, and visualize different network topologies while testing fault tolerance and performance metrics. It supports Java Swing and ASCII-based visualizations for real-time insights into network behavior.

A powerful simulation tool designed for creating and analyzing virtual networks with various topology structures. This simulator helps users gain insights into network performance, redundancy, and fault tolerance. It allows users to define nodes, customize topology structures, and visualize data paths in real-time using Java Swing or ASCII-based representations. Additionally, it provides performance metrics to compare the efficiency and resilience of different topologies.

Key Features
1. Network Design and Topology Selection
Node Definition: Users can specify the number of nodes (devices) and assign unique identifiers (e.g., names, IPs).
Supported Topologies: Select from multiple network structures, including:
Bus: Nodes connected in a linear fashion.
Star: A central hub connecting all nodes.
Ring: Nodes arranged in a closed-loop.
Mesh: Each node has multiple interconnections.
Tree: Represents a hierarchical arrangement.
Hybrid: A mix of different topology types.
Connection & Weight Configuration:
Define node connections and assign cable types (e.g., twisted pair, coaxial) to simulate data transfer times.
Underlying Data Structures:
Array for Bus topology.
Tree for hierarchical topologies.
Circular Linked List for Ring topology.
Graph for Mesh and Hybrid structures.
Outputs:
Graphical representation of the network using Java Swing or ASCII.
An adjacency matrix displaying connections, link types, and transmission delays.


2. Fault Tolerance and Redundancy Testing
Failure Simulation: Evaluate the network’s resilience by simulating node or link failures.
When a node or connection fails, the simulator recalculates alternative paths if available.
Observations:
Different topologies exhibit varying levels of robustness (e.g., Mesh networks offer multiple failover paths, while Rings have single points of failure).
User Inputs:
Select specific nodes or links to disable for testing fault tolerance.
Results:
Updated visualization of the network with failure scenarios.
A summary of network behavior, including affected connections and rerouted paths.


3. Performance Metrics and Analysis
Key Performance Indicators:
Transmission Time: The average time or hops required for data transfer across the network.
Node Accessibility: The percentage of nodes that remain reachable when certain links or nodes are disabled.
Network Resilience: The network’s ability to withstand failures.
Comparative Analysis: Evaluate different topologies based on speed, reliability, and redundancy.
Output Format:
A metrics dashboard summarizing results for each topology.
Graphs or tables comparing transmission time, reachability, and robustness.

4. Broadcast Simulation
Broadcast Functionality: Simulate data transmission from a single source node to all other nodes in the network.
Optimized Transmission: Uses Prim’s Algorithm to compute the most efficient broadcast paths.
User Input:
Select the source node for the broadcast.
Generated Results:
Visual representation of the broadcast paths using Java Swing and ASCII.
Calculation of the total transmission cost for reaching all nodes.
Technologies & Tools
Language: Java
Visualization: Java Swing for graphical display and ASCII for text-based visualization.
Data Structures Utilized:
Array/List for Bus topology.
Tree Structures for hierarchical topologies.
Circular Linked List for Ring topology.
Graph Representation for Mesh and Hybrid networks.

This project serves as an interactive platform for understanding and analyzing network topologies, offering valuable insights into network efficiency, fault tolerance, and performance trade-offs
