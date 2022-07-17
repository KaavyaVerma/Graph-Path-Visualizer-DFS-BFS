# Graph-Path-Visualizer-DFS/BFS
Visualization tool for pathfinding algorithms like DFS, BFS implemented in Python and Pygame.Users can Create nodes on the canvas, select created nodes, remove nodes (if needed) choose a start node and a target/end node then these algorithms to visualize and understand there working.
2 algorithms implemented for visualization:
->DFS
,BFS
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
![default_node](https://user-images.githubusercontent.com/90963546/179389306-47806506-de03-4b80-9b29-3e98cd71e8b2.png)| Default node |
![selected_node](https://user-images.githubusercontent.com/90963546/179389351-82a45720-121a-4529-bf0f-8a915d0ee035.png)| Selected node |
![start_node](https://user-images.githubusercontent.com/90963546/179389358-48ce3c6a-c2cc-41d8-a263-897bb6c69d81.png)  | Start node |
![end_node](https://user-images.githubusercontent.com/90963546/179389375-19ca6166-e018-4945-9126-9e597d5284ac.png)| End/Target node |
![waiting_node](https://user-images.githubusercontent.com/90963546/179389440-57040412-9c01-4d5c-9415-735d7e2bab56.png) | Waiting (Node is on the algorithms "waitlist" to be viewed soon) |
![inspected_node](https://user-images.githubusercontent.com/90963546/179388136-bd202644-9062-4c47-af04-0354b1702d50.png) | Focused (Node is currently focused by the algorithm) |
 ![visited_node](https://user-images.githubusercontent.com/90963546/179388301-00c5740d-2b75-4872-8566-5e614bf0e0d5.png)| Already visited (Node was already visited by the algorithm) |
![part_of_final_path_node](https://user-images.githubusercontent.com/90963546/179388322-d6ce4ca0-e608-4b47-842d-8b29f278132a.png)| Final node (Node is part of the final path proposed by the algorithm) |
