# Network Communication Algorithms Implementation in Java

This project is an implementation of network communication algorithms in Java, specifically the Link State Routing and Broadcast Algorithms. The program allows nodes in a network to communicate with each other by constructing a matrix of neighbor relationships and broadcasting messages to all nodes. The Link State Routing Algorithm ensures that each node has the most up-to-date information on the network topology, while the Broadcast Algorithm ensures that messages are delivered to all nodes in the network, even if some nodes are unreachable or failed.

## Key Skills Demonstrated

- Java programming
- Networking concepts
- Graph theory and algorithms
- Understanding of Link State Routing and Broadcast Algorithms
- Algorithm implementation and testing

## Key Achievements

- Successfully implemented Link State Routing and Broadcast Algorithms in Java.
- Created a program that enables nodes to communicate with each other in the network and broadcast messages to all nodes.
- Tested the implementation by running the program on different network topologies and message sizes.

## Link State Routing Algorithm Used

The Link State Routing Algorithm is used to build a matrix of neighbor relationships for the entire graph, ensuring that each node has the most up-to-date information on the network topology. Each node in the network runs the algorithm in different rounds, updating the matrix with information about its neighbors and the weights on the edges between them. The algorithm also allows each node to update the weight on the edge when it changes.

## Broadcast Algorithm Used

The Broadcast Algorithm is used to ensure that messages are delivered to all nodes in the network, even if some nodes are unreachable or failed. When a node wants to broadcast a message, it sends the message to all its neighbors except for the node that originally sent the message. Each receiving node then forwards the message to all of its neighbors except for the node that it received the message from. This process continues until all the nodes in the network have received the message.
