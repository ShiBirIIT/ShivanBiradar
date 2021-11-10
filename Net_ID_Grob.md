# INVERSE PROBLEM in ELECTRIC CIRCUITS
  # Content
- Inverse Problems
- Applications
- Motivation
- Problem Statement
- Methodology

<div align="center">
  INVERSE PROBLEMS<br><br>
</div>
<div align="justify">
  The inverse problem arises from the need to interpret indirect and incomplete measurements. In an inverse problem, an unknown system is subjected to a known input, and the responses are measured. From the limited knowledge of the input, limited knowledge of the system and responses, the aim is to reconstruct the unknown system. This method of inverse analysis also applies to complex electrical networks. The solution of the inverse problems in electric circuits is the circuit topology, values of circuit elements, and time- dependent variations of sources required to achieve a specified circuit behaviour<br><br>
</div>
<div align="center">
  APPLICATIONS<br><br>
</div>

<div align="justify">
  
  ![compre_22-03-2021_FINAL_Page_04](https://github.com/ShivanB/Shivan-Biradar/blob/master/assets/img/compre_22-03-2021_FINAL_Page_04.jpg)
  ![compre_22-03-2021_FINAL_Page_05](https://github.com/ShivanB/Shivan-Biradar/blob/master/assets/img/compre_22-03-2021_FINAL_Page_05.jpg)
  
  </div>


<div align="center">
 MOTIVATION<br><br>
</div>

<div align="justify">
  
  ![compre_22-03-2021_FINAL_Page_19](https://github.com/ShivanB/Shivan-Biradar/blob/master/assets/img/compre_22-03-2021_FINAL_Page_19.jpg)
  
  </div>
  
<div align="justify">
The inverse problems concerning electric circuits are not well studied as in the case of inverse problems in medical imaging, geology and astronomy.
There exist few graph theoretic methods (for inverse problems in electric circuits) for specific circuit topologies like the circular planar circuits, medial
graphs like structured circuit. Therefore, first and foremost challenge is to justify whether it is even possible to extract the solution (circuit topology,
parameter values, etc.) using the obtained responses/measurements through a mapping function (algorithm)?. There are no known universal
strategy/methods for calculating such maps since mapping function differs from topology to topology. <br>
The first proposed goal would be:<br>
1. An efficient "generalised" graph-theoretic method for inverse problems in electric circuits will be developed. This novel graph theoretic method will result in a set of feasible solutions.<br><br>
As a first step towards this we goal we propose a method, which is explaned below.<br><br>   
</div>


 <div align="justify">
  
  ![compre_22-03-2021_FINAL_Page_9](https://github.com/ShivanB/Shivan-Biradar/blob/master/assets/img/compre_22-03-2021_FINAL_Page_09.jpg)
  ![compre_22-03-2021_FINAL_Page_7](https://github.com/ShivanB/Shivan-Biradar/blob/master/assets/img/compre_22-03-2021_FINAL_Page_07.jpg)
  
  </div>

<div align="justify">
Any graph, directed or undirected, their characteristics are well defined by a matrix (like incidence matrix, adjacency matrix, etc.). Also, corresponding to a graph, various distance metrics are defined like the Kirchhoff’s distance, the Hamming distance, the Jaccard distance and many more. These metrics essentially characterise the structural properties like criticality of a graph and betweenness of nodes or edges. We propose to use one of the distance metrics i.e. resistance distance. Which is defined as:<br><br>
  
  ![compre_22-03-2021_FINAL_Page_8](https://github.com/ShivanB/Shivan-Biradar/blob/master/assets/img/compre_22-03-2021_FINAL_Page_08.jpg)

  
<div>
  
Assumptions:<br>
- Circuit topology unknown.<br>
- Some terminals available for measurements.<br>
- Total number of nodes of the circuit known.<br>
- All the resistance in the circuit is 1Ω.<br>
- Terminal index and vertex index are known.<br>
- No voltage source in the circuit.<br><br>
<div align="center">
  
 First Step in Strategy: Performing experiments<br><br>
  
</div>
  
 ![compre_22-03-2021_FINAL_Page_11](https://github.com/ShivanB/Shivan-Biradar/blob/master/assets/img/compre_22-03-2021_FINAL_Page_11.jpg)<br>

<div align="center">
  
 Second Step in Strategy:  The measured response is used to calculate effective resistance, which
is used to form a resistance distance matrix 𝑅<sub>d</sub> <br><br>
  
</div>
  
 ![compre_22-03-2021_FINAL_Page_11](https://github.com/ShivanB/Shivan-Biradar/blob/master/assets/img/compre_22-03-2021_FINAL_Page_12.jpg)
  
<div align="center">
  
 Third Step in Strategy:  Once the 𝑅<sub>d</sub> matrix is formed, we use definition to relate Laplacian
matrix to resistance distance.  <br><br>
  
</div>
  
  ![compre_22-03-2021_FINAL_Page_11](https://github.com/ShivanB/Shivan-Biradar/blob/master/assets/img/compre_22-03-2021_FINAL_Page_12.jpg)
  
 <div align="center">
  
 Third Step in Strategy: We derive following polynomial equations from the resistance distance matrix, taking the help of the property of Laplacian matrix<br><br>
  
</div> 
  
  ![compre_22-03-2021_FINAL_Page_13](https://github.com/ShivanB/Shivan-Biradar/blob/master/assets/img/compre_22-03-2021_FINAL_Page_13.jpg)
  
 <div align="center">
  
 Forth Step in Strategy:  Solve the system of nonlinear functions using Groebner basis.<br><br>
  
</div>
  
   ![compre_22-03-2021_FINAL_Page_14](https://github.com/ShivanB/Shivan-Biradar/blob/master/assets/img/compre_22-03-2021_FINAL_Page_14.jpg)
