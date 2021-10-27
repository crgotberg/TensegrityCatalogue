INPUT FILES:
Input files contain descriptions of shapes of possible research interest. There are four elements describing each shape:
  1) A friendly name usually identical to the polyhedron ('Cube')
  2) A neighbor matrix (adjacency matrix but with a main diagonal of ones) describing the cable edges of the shape
  3) The positions of each node of the shape (every row is a node)
  4) All possible relabellings of those nodes which preserve the structure of the adjacency matrix (every row is a different labelling)

RESULTS FILES:
Result files are the results of specific tests using the algorithm. Four elements compose each set of files (with subparts):
  1) A friendly name as above, which indicates which input files were used in the test
  2) Cosntraints used in testing
    a) Minimum node degree
    b) Maximum node degree
    c) Elimination of isomorphic results
    d) Restriction of edges on external faces
    e) Restriction of edges used by the cables
    f) Minimum number of connected components
    g) Maximum number of connected components
    h) Maximum number of elements in any connected component
  3) A list of edges struts use in the solution set (each row corresponds to an edge and edge lists in the solution set reference rows here instead of edges)
  4) A list of strut edge sets meeting the constraints, referencing 3) to conserve space
