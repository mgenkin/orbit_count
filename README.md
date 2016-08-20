# Orbit Count

Counting orbits.  First the n-holed sphere, next the we conquer the world.

## Algorithm

- Generate basepoint diagrams for self-intersection n

- Generate graphs for each basepoint diagram (decide edge connectivity)

- Test graphs for planarity

- Check number of bigons and 1-gons (throw if there's more than boundary components)

- Test for multicurve

- Enumerate ways to distribute boundary components

## Classes

- SphereOrbit
  * AdjacencyMatrix (2d array)
  * BasePointDiagram
  * bunch of Face
  * comparator method

- Face
  * comparator method

- BasepointDiagram
  * comparator method (maybe)

