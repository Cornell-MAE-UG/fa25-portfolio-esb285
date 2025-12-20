---
layout: project
title: Heat Exchanger Analysis
description: Analysis of Heat Exchanger for Thermodynamic Course
technologies: [None]
image: /assets/images/actual_images_used/IMG_2759.jpeg
---

For my thermodynamics course, I was tasked with analyzing a thermodynamics system in the real world using thermodynamic concepts. A minilab with a heat exchanger was done for this project. 

**Set Up of Mini-lab**

The set up contained four containers: one with hot (red) water, one with cold (blue) water, and two empty containers. The hot water was heated using heat pump and the cold water was cooled using ice. The temperatures measured during this experiment were determined using a thermometer for the water. After each run, water from the two previously empty containers were returned to their respective initial containers and either heated back up or cooled down. 

Below is an image of the initial set up with the heat exchanger:

![Hand-calculation Diagrams]({{ "/assets/images/actual_images_used/IMG_2755.jpeg" | relative_url }}){: .center-image style="width: 500px"}

Three runs were done for this lab, each with different conditions. The data collected from each run is documented below.

<table class="centered-table">
  <thead>
    <tr>
      <th>Run</th>
      <th>T<sub>H, i</sub></th>
      <th>T<sub>H, f</sub></th>
      <th>T<sub>C, i</sub></th>
      <th>T<sub>C, f</sub></th>
    </tr>
  </thead>

  <tbody>
    <tr>
    <td>Run 1</td><td>45.0</td><td>27.3</td><td>8.0</td><td>23.6</td>
  </tr>
  <tr>
    <td>Run 2</td><td>40</td><td>20.3</td><td>6.3</td><td>24.5</td>
  </tr>
  <tr>
    <td>Run 3 </td><td>39.4</td><td>19.6</td><td>9.4</td><td>21.2</td>
  </tr>
  </tbody>
</table>

The first run was done with parallel flow with the pumps running at the same speed of +1. The speed of the water flow was not obtained in this experiment. 

Using the following analysis, the heat per mass output can be calculated, assuming steady state, no work done and negligible changes in kinetic and potential energies. The steady state assumption is based on the fact that there was no disturbance in the flow during the run. There were also no observable changes in height or speed of the water so kinetic and potential energy changes can be neglected. The specific heat used is 4.18 kJ/ kg * °C as that is the average specific heat for water at atmospheric pressure between temperatures of approximately 4-40 °C. The mass flow, m_dot, for the hot and cold water was assumed to be the same as the pumps were both at the same setting.

![Hand-calculation Diagrams]({{ "/assets/images/actual_images_used/IMG_2330.JPG" | relative_url }}){: .center-image style="width: 500px"}

As shown the heat per mass output is 8.78 kJ/kg. This run shows that there is heat being lost to the surroundings and that it is not a perfectly closed system as well as not adiabatic. This is observable through the change in temperature of the surface of the heat exchanger while the system is operating.

For the second run, the heat exchanger was run in counterflow with the pumps running at the same speed of +1. 

The same assumptions from run 1 were used in the analysis of the data as shown below. 

![Hand-calculation Diagrams]({{ "/assets/images/actual_images_used/IMG_2331.JPG" | relative_url }}){: .center-image style="width: 500px"}

The heat per mass output for run 2 was 6.27 kJ/kg. This run has a smaller heat loss compared to run 1 and the change in temperatures of both waters is higher in run 2 than it was in run 1, which seems to suggest that having the heat exchanger in counterflow is more effective. However, due to the lack of trials done, this cannot be proven for this specific heat exchanger. 

For the third run, the heat exchanger was run in counterflow with the pumps running at different speeds: the hot water running at -1 and the cold running at +1. Again, the water flow was not determined experimentally.

The same assumptions except about the mass flow were used in analysing run 3. 

![Hand-calculation Diagrams]({{ "/assets/images/actual_images_used/IMG_2332.JPG" | relative_url }}){: .center-image style="width: 500px"}

As shown, the heat per mass output can not be determined from the data collected, due to the mass flows of the waters being different. However, if the heat per mass output is assumed to be within 6-8 kJ/kg as it was for the other runs, the difference in mass flow can be theoretically calculated. Knowing that the hot water was running slower than the cold water, the mass flow of the hot water can be said to have been 0.67-0.7 times the flow of the cold water. This analysis is based on the assumption that the heat output is remaining similar to the past experiments and would need to be confirmed with further experiments and data collection. 

**Discussion**

From data, the counterflow seems to be more effective in changing the temperatures of the water. Also, having different speeds seems to lead to larger differences in changes in temperature between the hot and cold water. This may stem from the fact that the hot water was in contact with the heat exchanger longer due to the slower mass flow, leading to more transfer of heat for the hot water. 