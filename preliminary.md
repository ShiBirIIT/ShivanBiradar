# PRELIMINARIES
Suppose an electrical network is inside a black box. The interior of the box consists of nodes joined by conductors. The nodes are the vertices, and the conductors are the edges of a graph **G**.

## INVERSE PROBLEM
Is to find the conductance of each edge in **G** from measurements of voltages and currents at the boundary nodes.

## FORWARD PROBLEM
The forward problem assumes that the graph G and the conductance **&gamma;(pq)** of each edge pq in **G** are known. If a voltage is imposed at the boundary nodes, there is a function **u** defined throughout the network which agrees with **f** at the boundary nodes, and which satisfies Kirchhoff's Law at each interior node.

This function **u** is called the potential due to **f**. The resulting current at
the boundary nodes is called the network response. The linear map &Lambda; which takes the boundary voltage **f** to the boundary current &phi; is called the response map. &Lambda; is sometimes called the voltage-to-current map because it gives the current (i.e., the response) to any voltage imposed at the boundary nodes. The response map will be known when the potential is found for each boundary function **f** , and the resulting boundary current &phi; is calculated.

## CIRCULAR PLANAR GRAPH
A graph with boundary is a triple **G = (V, V<sub>B</sub>, E)**, where V is the set of nodes and E is the set of edges for a finite graph, and V<sub>B</sub> is a nonempty subset of V called the set of boundary nodes. The set I = V — V<sub>B</sub> is called the set of interior nodes. 
A circular planar graph is a graph **G** with boundary which is embedded
in a disc **D** in the plane so that the boundary nodes lie on the circle **C** which bounds **D**, and the rest of **G** is in the interior of **D**. The boundary nodes are labeled v<sub>1</sub>,..., v<sub>n</sub> in clockwise order around **C**.\
\
If p and q are distinct boundary nodes, a path &beta; from p to q through **G**, consists of a sequence of edges: e<sub>0</sub> = pr<sub>1</sub>, e<sub>1</sub>=r<sub>1</sub>r<sub>2</sub>,..., e<sub>h-1</sub> =
r<sub>h-1</sub>, e<sub>h</sub>=r<sub>h</sub>q,
eh = rh1 such that r<sub>1</sub>,r<sub>2</sub>,.. . ,r<sub>h</sub> are distinct interior nodes of G.
