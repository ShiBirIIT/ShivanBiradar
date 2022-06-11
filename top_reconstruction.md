# Network Topology Reconstruction of Circular Planar Electrical Network Kalmanson criteria
# INTRODUCTION
Electrical network topology reconstruction is an ill-posed
problem and, in general, has many solutions. Network topol-
ogy reconstruction involves simultaneously identifying elec-
trical network structure and edge resistor values. This area of
research has seen significant interest among researchers due
to its applications in a wide range of areas, such as system
biology [1], geology [2], medical imaging [3], and power
system networks [4]. Two primary objectives that are broadly
considered in electrical network topology reconstruction are:
i) to determine the conductivity distribution of the electrical
network using the measurements of voltages and current at
the boundary nodes and ii) to find the conductance of each
edge in the electrical network [5]. 

<div align="justify">
  
  ![motivation](https://github.com/ShivanB/Shivan-Biradar/blob/master/assets/img/motivation.jpg)

  </div>
  
# MOTIVATION
What is inside the black box electrical network?, can the boundary measurements uncover the hidden truth?, Are all the boundary terminals available for the measurements? and can we reconstruct a uniques electrical network with the limitedly available boundary measurements?. These are the important questions which the motivates the problem. Various reseach studies has posed various solutions to the problem. There are still some untouched problem like reconstructing the electrical network using the partial boundary measurments. And also, constructing all possible networks corresponding to the collected boundary data.

# Literature Survey
It has been shown in [5] that if the response matrix (Λ)
satisfies the condition of a non-negative circular minor for
a circular planar electrical network, with all the boundary
terminals available, then we can reconstruct both the topol-
ogy of the planar network and the edge conductance of
the network. In [6], the authors present an approach for
calculating the conductor values in a circular planar passive
resistor network, using voltages and currents measured at
the boundary. Assuming that only the network structure is
known and all the boundary terminals are available, a γ-
harmonic function on the circular network is defined. Then
using the harmonic continuation and Λ, the conductor values
are computed. In [7], it is shown that if G is any critical
[5] circular planar graph corresponding to the circular planar
resistor network with all boundary terminals available for
collecting data, the conductor values can be computed using Λ.
Recent work in phylogenetics has also concentrated on similar
reconstruction problems, as seen in [8] and [9]. Phylogenetic
and electrical networks are combinatorially identical objects
[9]; however, the edge weights are less well understood in
phylogenetic networks [10]. Electrical networks have been
traditionally weighted with conductance, whereas phylogenetic
networks have traditionally been weighted with statistical
distance measures. However, there is a straightforward analogy
between the two paradigms: the genetic distance between two
existing taxa (species or individuals) can be compared to the
resistance distance [11] between two exposed terminals. In [9],
assuming that all the boundary terminals and response matrix
are already available, the authors find a corresponding split
network [12]. The split network yields the bridge structure
of the unknown network, which is used to reconstruct the
local graph. However, to the best of our knowledge, there are
no general methods that consider partially available boundary
terminals and fail to list all the possible non-unique electrical
networks corresponding to the collected limited boundary data.
In this article, we consider a circular planar passive-resistive
network with no interior nodes; we show that the limitedly
available data collected from the experiments done on the
exposed boundary terminals can be used to design a resistance
distance matrix RD. The unknowns in the RD can be posed as
a set of multivariate polynomials F. Since these polynomials
are huge and increase in number with a decrease in the
availability of boundary terminals. Gr ̈obner basis is calculated
corresponding to F, and a list of all possible solutions to the
Gr ̈obner basis is all possible non-unique electrical network
topologies with their edge conductance values.

# PRELIMINARIES


https://github.com/ShivanB/Shivan-Biradar/blob/master/preliminary.md
# References
[1] Asadi, Behrang. Network Reconstruction of Dynamic Biological Sys-
tems. University of California, San Diego, 2013.\
[2] Boo, Chang-Jin, Ho-Chan Kim, and Min-Jae Kang. ”2D Image Recon-
struction of Earth Model by Electrical Resistance Tomography.” Journal
of the Korea Academia-Industrial cooperation Society 14.7 (2013):
3460-3467.\
[3] Bianchessi, Andre, et al. ”Electrical impedance tomography image
reconstruction based on neural networks.” IFAC-PapersOnLine 53.2
(2020): 15946-15951.\
[4] Napoletani, Domenico, and Timothy D. Sauer. ”Reconstructing the
topology of sparsely connected dynamical networks.” Physical Review
E 77.2 (2008): 026103.\
[5] Curtis, Edward B., and James A. Morrow. Inverse problems for electrical
networks. Vol. 13. World Scientific, 2000.\
[6] Curtis, Edward, Edith Mooers, and James Morrow. ”Finding the con-
ductors in circular networks from boundary measurements.” ESAIM:
Mathematical Modelling and Numerical Analysis 28.7 (1994): 781-814.\
[7] Curtis, Edward B., David Ingerman, and James A. Morrow. ”Circular
planar graphs and resistor networks.” Linear algebra and its applications
283.1-3 (1998): 115-150.\
[8] Huber, Katharina T., et al. ”Reconstructibility of level-2 unrooted
phylogenetic networks from shortest distances.” arXiv e-prints (2021):
arXiv-2101.\
[9] Forcey, Stefan, and Drew Scalzo. ”Phylogenetic networks as circuits
with resistance distance.” Frontiers in Genetics (2020): 1177.\
[10] Huson, Daniel H., and David Bryant. ”Application of phylogenetic
networks in evolutionary studies.” Molecular biology and evolution 23.2
(2006): 254-267.\
[11] Klein, Douglas J., and Milan Randi ́c. ”Resistance distance.” Journal of
mathematical chemistry 12.1 (1993): 81-95.\
[12] Minh, Bui Quang, et al. ”Budgeted phylogenetic diversity on circular
split systems.” IEEE/ACM Transactions on Computational Biology and
Bioinformatics 6.1 (2008): 22-29.\
[13] Bapat, Ravindra B., Ivan Gutmana, and Wenjun Xiao. ”A simple method
for computing resistance distance.” Zeitschrift f ̈ur Naturforschung A
58.9-10 (2003): 494-498.\
[14] Czapor, Stephen R., and Keith O. Geddes. ”On implementing Buch-
berger’s algorithm for Grobner bases.” Proceedings of the fifth ACM
symposium on Symbolic and algebraic computation. 1986.\
