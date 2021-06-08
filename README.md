# Force_Directed_Graph_Layout


a. Adding node labels: A node label (the node name, i.e., the source) is shown below each node. If a node is dragged, its label moves with it. 


b. Styling links: Links are styled based on the “value” field in the links array. Following styles are assigned:


If the value of the edge is equal to 0, the link becomes green and thick.

If the value of the edge is equal to 1, the link becomes blue and thin.


c. Scaling node sizes: 

Radius of each node in the graph is scaled based on the degree of the node (Linear scale is used by any other scale choice can be made).

Note: Regardless of which scale we use, we should avoid extreme node sizes (e.g., nodes that are mere points, or barely visible, as well as very large nodes). Failure to do so may result in a poor quality visualization. 



![image](https://user-images.githubusercontent.com/8483205/121184473-bd987900-c82a-11eb-8bf6-d72a35bc3dcf.png)



d. Pinning nodes (fixing node positions):

when a node is double clicked, it pins the node’s position such that it will not be modified by the graph layout algorithm (note: pinned nodes can still be dragged around by the user but they will remain at their positions otherwise). Node pinning is an effective interaction technique to help users spatially organize nodes during graph exploration.
Mark pinned nodes to visually distinguish them from unpinned nodes, e.g., pinned nodes are shown in a different color, border thickness or visually annotated with an “asterisk” (*), etc.
Double clicking a pinned node unpins (unfreeze) its position and unmarks it.


![image](https://user-images.githubusercontent.com/8483205/121184281-8c1fad80-c82a-11eb-8ab7-557d134a7d01.png)

