# Ideas

## Vocab

* Candidat : a set of plan, one per agent. Each plan works indivisualy, but the set may conflict.
* Solution : a candidat without conflict.

## Tools

* Ordering graph
  * Given a candidat, we can define a graph. The nodes are the actions (the vertices? both?), the edge are "succession" condition.
  * A candidat may have multiple graphs (different working ordering), one or no graph.
  * A constraint graph is a waighted ordering graph

* Difference logic
  * Given an constraint graph, we get a solution (if possible).

* Critical path
  * Given a candidat, we can use the ordering graph to get the critical path.

* Pseudo-conflict
  * Given a candidate, we can define pseudo-conflict.

## Ideas

* [ ] We take an instance, we find shortest path (we get lower bound), we convert them to a candidate, we make an ordering graph and we get a solution from it (we get upper bound).
* [ ] We take an instance, we find shortest path, we convert them to a candidate, we make ordering graphs and we get solutions from it. (wanko's encoding)
* [ ] We take an instance, we find shortest path, we look pseudoconflict, we define trails with no more pseudoconflict, we convert them to a candidate, we make ordering graphs and we get solutions from it.
* [ ] We take an instance, we find shortest path, we look pseudoconflict, we define special trails with no more pseudoconflict called detour, we convert them to a candidate, we make ordering graphs and we get solutions from it.
* [ ] We take an instance, we find shortest path, we define special trails called detour, we convert them to a candidate, we make ordering graphs and we get solutions from it.
* [x] We take an instance, we find trails, we convert them to a candidate, we make ordering graphs and we get solutions from it.
  * Make variants
