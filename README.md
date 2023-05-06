Download Link: https://assignmentchef.com/product/solved-ee6506-assignment-2
<br>



<ol>

 <li>According to the Gauss quadrature rule, an integral is expressed as a weighted sum of <em>n </em>terms in the form: <em><sup>n</sup></em><sub>=1 </sub><em>w<sub>i </sub>f</em>(<em>x<sub>i</sub></em>), where <em>w<sub>i</sub></em>, <em>w</em><sub>2</sub>, ··<em>w<sub>n </sub></em>are unknown coefficients known as weights and <em>x</em><sub>1</sub>, <em>x</em><sub>2 </sub>··· <em>x<sub>n </sub></em>are the discretization points. Construct a Gauss quadrature rule and use it to evaluate the following integral:<span style="text-decoration: line-through;">√</span><em><sup>e</sup></em><em>x</em><em><sup>x</sup></em><sub>2 </sub><em>dx</em>. In addition:

  <ul>

   <li>Plot the function in the interval [0.1 – 4.9].</li>

   <li>Show the development of the quadrature rule, noting that the limits asked above are non-standard. Bonus points if you derive the nodes and weights using symbolic math in MATLAB.</li>

   <li>Study the accuracy of your rule as a function of the number of quadrature points, while comparing your output with the <em>integral </em>command in MATLAB for the same evaluation.</li>

  </ul></li>

 <li>A thin metallic cylinder of length <em>L </em>and radius <em>a</em>, along the <em>y </em>− <em>axis </em>as shown in the figure. The electrostatic potential on the cylinder is given as 1V. Using point matching and expressing the surface charge density <em>ρ<sub>s </sub></em>in terms of a line charge density <em>ρ<sub>l</sub></em>, in turn expressed via a pulse basis expansion:</li>

</ol>

<em>N ρ<sub>l </sub></em><sup>= </sup>∑ <em>a<sub>n</sub>g<sub>n</sub></em>(<em>y</em>), <em>ρ<sub>l </sub></em>= 2<em>πaρ<sub>s</sub></em>,

<em>n</em>=1

solve the following:

<ul>

 <li>find and plot the surface charge density on the cylinder <em>ρ<sub>s</sub></em>,</li>

 <li>plot the potential <em>V </em>over the surface of the sphere with radius 10m.</li>

</ul>

Assume cylinder length <em>L </em>= 1<em>m</em>, and radius <em>a </em>= 0.01<em>m</em>. It is recommended to at least use a 3-point Gauss-quadrature rule to evaluate the integrals. Bonus points if you can justify the choice of the number of quadrature points; also if you can re-use some code from Q1 here.