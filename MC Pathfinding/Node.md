A node is sort of a cost-annotated waypoint.

It contains a xyz set of coordinates, but it also contains the A* g, h, and f scores.

Their creation is handled by the NodeEvaluator, and they are cached in a NodeMap