# Graph-Path-Visualizer-DFS/BFS
Visualization tool for pathfinding algorithms like DFS, BFS implemented in Python and Pygame.Users can Create nodes on the canvas, select created nodes, remove nodes (if needed) choose a start node and a target/end node then these algorithms to visualize and understand there working.
2 algorithms implemented for visualization:
->DFS
->BFS
The visualization consists of nodes and connections between them (paths). Each node and each connection can be manually added or removed.

### Controls
Action | Controls |
--- | --- |
Create node | **Mouse_left_click** on free space |
Remove node | Position mouse cursor on existing node + key **'r'** |
Select node | **Mouse_left_click** on existing (unselected) node |
Unselect node | **Mouse_left_click** on existing (selected) node |
Mark start node | Position mouse cursor on existing node + key **'s'** |
Mark end node | Position mouse cursor on existing node + key **'e'** |
Connect nodes | key **'c'** (connects all selected nodes) |
Disconnect nodes | key **'d'** (disconnects all unselected nodes) |
Start breadth-first visualization | key **'1'** |
Start depth-first visualization | key **'2'** |
Stop/Reset algorithm progress | key **'SPACE'** |
### Legend
Symbol/ Color | State |
--- | --- |
![Default node](img/default_node.PNG?raw=true "Default node") | Default node |
![Selected node](img/selected_node.PNG?raw=true "Selected node") | Selected node |
![Start node](img/start_node.PNG?raw=true "Start node") | Start node |
![End node](img/end_node.PNG?raw=true "End node") | End/Target node |
![Waiting node](img/waiting_node.PNG?raw=true "Waiting node") | Waiting (Node is on the algorithms "waitlist" to be viewed soon) |
![Inspected node](img/inspected_node.PNG?raw=true "Inspected node") | Focused (Node is currently focused by the algorithm) |
![Visited node](img/visited_node.PNG?raw=true "Visited node") | Already visited (Node was already visited by the algorithm) |
![Final node](img/part_of_final_path_node.PNG?raw=true "Final node") | Final node (Node is part of the final path proposed by the algorithm) |

     
