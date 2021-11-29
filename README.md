# 3coloring
custom multiprocess 3coloring solver in C

### Description
A detailed description of the functionality can be found at [3coloring.pdf](3coloring.pdf)

A supervisor can be started to collect 3coloring results from generators. Multiple generators can be started afterwards to generate random results.
The supervisor will collect all results and store the best one. The number of edges that need to be removed in order to be 3colorable will be printed to stdout.

The supervisor will automatically terminate if the graph is proved to be 3colorable. If the supervisor is interrupted it will also terminate all active generators.

### Synopsis

```
  supervisor
  generator EDGE1...
```
