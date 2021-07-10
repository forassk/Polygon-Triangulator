# Polygon-Triangulator
- Implementation of the Triangulation of an n-sided polygon in **O(n^2)** and **O(nlogn)** time and visualisation using **graphics.h**.
- O(n^2) method for **simple** polygons: finding all ears, forming diagonals and pruning ear-list recursively.
- O(nlogn) method for **monotone** polygons: splitting into monotone chains and adding diagonals using stack.
