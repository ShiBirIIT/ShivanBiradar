# RESISTANCE DISTANCE
In graph theory, the resistance distance between two vertices of a simple connected graph, G, is equal to the resistance between two equivalent points on an electrical network, constructed so as to correspond to G, with each edge being replaced by a 1 ohm resistance. It is a metric on graphs.
The resistance distance (with circuit containing only 1 ohm resistance) r<sub>ij</sub> between terminals i and j.\

<p align="center">
   r<sub>ij</sub>=det[L(i,j)]/det[L(i)].
</p>

Here, L(i,j) is the submatrix of L, obtained by deleting i<sup>th</sup>, j<sup>th</sup> row and i<sup>th</sup>, j<sup>th</sup> column. L(i) is a submatrix obtained by deleting i<sup>th</sup> row and i<sup>th</sup> column. 

When the circuit contains resistances other than 1 ohm. The resistance distance is defined as:

<p align="center">
   r<sub>ij</sub>=x<sub>ii</sub>+x<sub>jj</sub>-2xx<sub>ij</sub>.
</p>
The resistance distance of an electrical circuit with arbitrary resistance value is a symmetric matrix R<sub>D</sub>, defined as:
<p align="center">
  R<sub>D</sub> = X<sub>p</sub>J + JX<sub>p</sub> - 2X
</p>
  Here, X<sub>p</sub> is a diagonal matrix, whose diagonal values are equal to diagonal values of matrix X. J is a square matrix of ones.
  
 <p align="center">
  X=(L+(1/n)J)<sup>-1</sup>
</p>

 
