OpenSCADPolyhedron
==================

Julia modules to help build complex, repeating polyhedrons in OpenSCAD.

The OpenSCADPolyhedron module helps generate complex polyhedron commands for OpenSCAD.
The key function is generatePolyhedron, which takes an initial set of points
and faces, a set of transformations, and a dictionary of symmetries. All the
transforms are applied to the initial base polyhedron, resulting in a new set
of points and faces. The symmetry dictionary is used to eradicate
duplicate points, so that the resulting polyhedron can be described as simply
as possible.
