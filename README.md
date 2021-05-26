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
<p>3) The distance between the car and the pedestrian is unknown</p>


<h3>Solution:</h3>
<p>In order to get the best angle with maximum probability of crossing the road before the car approaches ---- when the pedestrian crosses the road, the distance between the car and him/her must be maximum</p>

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
  alt="VSCode Blockman Icon"
  width="800px"
/></p>

<h3>Answer:</h3>
<p>α = arcsin(1/n)</p>

<h3>Geogebra plot:</h3>
<p>y = b + d ⋅ tan(α) - n⋅V⋅d/(V ⋅ cos(α))</p>
<p>and</p>
<p>α = arcsin(1/n)</p>
<a href="https://www.geogebra.org/m/YV7g2YKA">https://www.geogebra.org/m/YV7g2YKA</a>
