# Cycle detection in graphs using C++

This program allows you to create and manipulate a graph by adding and removing edges between vertices. It also provides the functionality to print the connections in the graph and checks for cycles whenever an edge is added.

## Installation

1. Clone the repository to your local machine.
2. Compile the code using a C++ compiler.
3. Execute the compiled program.

## Usage

1. Upon launching the program, you will be prompted to specify the number of vertices in the graph. The valid range for the number of vertices is between 1 and 50.
2. After entering the number of vertices, a new graph will be initialized.
3. You will be presented with a user guide that explains the available actions.
4. Choose one of the following actions:
   - `a`: Add an edge between two vertices.
   - `d`: Remove an edge between two vertices.
   - `p`: Print the connections in the graph.
   - `q`: Quit the program.
5. Follow the prompts to provide the necessary information for each action.
6. If an edge is added and a cycle is detected, the graph will terminate and print the final graph form.
7. After each action, you will be prompted to choose another action until you decide to quit the program.
8. If you wish to create a new graph, you can choose to do so after terminating the current graph.

## Example

```
<_###_> Initializing a new graph <_###_>

<_#_> Specify the number of vertices in this graph? <_#_>
# V >> 5

<_#_> User Guide <_#_>
> The index of vertices starts from 1 up to 5
> Input 'a' to add an edge between 2 vertices
> Input 'd' to remove an edge between 2 vertices
> Input 'p' to print the connections in the graph
> Input 'q' to finish editing the graph
> The code checks for a cycle each time an edge is added

**********************

<> Choose Action <>
a: add_edge   d: delete_edge   q: quit   p: print
action > a

Add edge
> from node >> 1
> to node >> 2

>> Adding edge <<
Cycle detected?  >> NO

**********************

<> Choose Action <>
a: add_edge   d: delete_edge   q: quit   p: print
action > p

Connections in the graph:
Vertex 1: [2]
Vertex 2: []

**********************

<> Choose Action <>
a: add_edge   d: delete_edge   q: quit   p: print
action > q

!___TERMINATING GRAPH___!

<_#_> New Graph? <_#_>
1: yes / 0: no >> 1
```

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please feel free to submit a pull request.
<!-- 
## License

This project is licensed under the [MIT License](LICENSE).
 -->
