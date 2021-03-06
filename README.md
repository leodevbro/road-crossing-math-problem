In Georgian (ქართული): https://drive.google.com/file/d/0B_4P3RNorJzTN3h0Z3cwaG04SXc
# Real life math problem and solution

<h3>Crossing The Road As A Pedestrian:</h3>
<p>The car has <strong>n</strong> times more speed than the pedestrian. What is the best <strong>α</strong> angle from the perpendicular to maximize the chance of crossing the road in time before the car approaches?</p>

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/road-crossing-math-problem/main/image/aa-intro.jpg"
  alt="VSCode Blockman Icon"
  width="1000px"
/></p>
<h3>Restrictions:</h3>

<p>1) n &gt; 1</p>
<p>2) 0 &leq; α &lt; 90°</p>
<p>3) The width of the road is unknown</p>
<p>4) The distance between the car and the pedestrian is unknown</p>



<h3>Solution:</h3>
<p>In order to get the best angle with maximum probability of crossing the road before the car approaches ---- when the pedestrian crosses the road, the distance between the car and him/her must be maximum:</p>

<p><strong>First, define the variables:</strong></p>
<p>Speed of the pedestrian — V</p>
<p>Speed of the car — n⋅V</p>
<p>Horizontal speed of the pedestrian — V<sub>x</sub></p>
<p>Vertical speed of the pedestrian — V<sub>y</sub></p>
<p>Horizontal distance between the first and the last point of the pedestrian — a (not α)</p>
<p>Horizontal distance between the car and the pedestrian — b</p>
<p>Width of the road — d</p>
<p>Time spent to cross the road — t</p>

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/road-crossing-math-problem/main/image/geo-scheme.jpg"
  alt="math formula"
  width="800px"
/></p>

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/road-crossing-math-problem/main/image/sn-01.png"
  alt="math formula"
/></p>

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/road-crossing-math-problem/main/image/sn-02.png"
  alt="math formula"
/></p>

<p><strong>b</strong> affects the maximum, but it does not affect the best angle to get maximum, so we can remove it.</p>

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/road-crossing-math-problem/main/image/sn-03.png"
  alt="math formula"
/></p>

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/road-crossing-math-problem/main/image/sn-04.png"
  alt="math formula"
/></p>

<p><strong>d</strong> affects the maximum, but it does not affect the best angle to get maximum, so we can remove it.</p>

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/road-crossing-math-problem/main/image/sn-05.png"
  alt="math formula"
/></p>

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/road-crossing-math-problem/main/image/sn-06.png"
  alt="math formula"
/></p>

<p>In order to find the extremum of a function, we must equalize its derivative to zero:</p>

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/road-crossing-math-problem/main/image/sn-07.png"
  alt="math formula"
/></p>

<p><strong>cos<sup>2</sup>(α)</strong> cannot be zero, so <strong>α</strong> cannot be 90°, and therefore:</p>

<p align="center"><img
  src="https://raw.githubusercontent.com/leodevbro/road-crossing-math-problem/main/image/sn-08.png"
  alt="math formula"
/></p>

<p>And finally, <strong>α = arcsin(1/n)</strong> because we already knew that <strong>0 &leq; α &lt; 90°</strong> and <strong>n &gt; 1</strong>.</p>

<h3>Answer:</h3>
<p>α = arcsin(1/n)</p>


<table>
  <thead>
    <tr>
      <th>n (n > 1)</th>
      <th>α (0 &leq; α &lt; 90°)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.1</td>
      <td>≈65.380023°</td>
    </tr>
    <tr>
      <td>1.5</td>
      <td>≈41.810315°</td>
    </tr>
    <tr>
      <td>2</td>
      <td>=30°</td>
    </tr>
    <tr>
      <td>3</td>
      <td>≈19.471221°</td>
    </tr>
    <tr>
      <td>4</td>
      <td>≈14.477512°</td>
    </tr>
    <tr>
      <td>5</td>
      <td>≈11.536959°</td>
    </tr>
    <tr>
      <td>10</td>
      <td>≈5.73917°</td>
    </tr>
    <tr>
      <td>15</td>
      <td>≈3.822554°</td>
    </tr>
    <tr>
      <td>20</td>
      <td>≈2.865984°</td>
    </tr>
    <tr>
      <td>50</td>
      <td>≈1.145992°</td>
    </tr>
    <tr>
      <td>100</td>
      <td>≈0.572967°</td>
    </tr>
    <tr>
      <td>1000</td>
      <td>≈0.057296°</td>
    </tr>
  </tbody>
</table>
<a href="https://www.rapidtables.com/calc/math/Sin_Calculator.html">Calculator used</a>


<br />
<br />
<br />



<h3>Geogebra plot:</h3>
<p>y = b + d ⋅ tan(α) - n⋅V⋅d/(V ⋅ cos(α))</p>
<p>and</p>
<p>α = arcsin(1/n)</p>
<a href="https://www.geogebra.org/m/YV7g2YKA">https://www.geogebra.org/m/YV7g2YKA</a>
