---
layout: project
title: Heat Exchanger Analysis
description: Analysis of Heat Exchanger for Thermodynamic Course
technologies: [MATLAB, Lab Equipment]
image: /assets/images/actual_images_used/heat_exchanger.jpeg
imagealt: Heat exchanger minilab experimental setup
imagecaption: Minilab Heat Exchanger System Setup
---

## Project Overview
For my thermodynamics course, I was tasked with analyzing a thermodynamics system in the real world using thermodynamic concepts. A minilab with a heat exchanger was done for this project.

### Objectives
The primary objective of the mini‑lab was to analyze a real‑world thermodynamic system—a small heat‑exchanger setup—using core concepts such as energy balance, heat transfer, and flow configuration effectiveness. The experiment aimed to compare parallel‑flow and counterflow heat‑exchange behavior, quantify heat transfer using measured temperature changes, and evaluate how flow direction and pump speed influence thermal performance. A secondary objective was to assess whether the system behaved as an ideal closed, adiabatic system or whether measurable losses to the surroundings occurred.

### Process
The experimental process involved constructing a four‑container system with hot and cold water reservoirs connected through tubing and a heat exchanger. Hot water was heated using a heat pump, while cold water was cooled using ice. Three experimental runs were performed: parallel flow at equal pump speeds, counterflow at equal pump speeds, and counterflow with unequal pump speeds. For each run, initial and final temperatures of both streams were recorded after reaching steady‑state conditions. Using the steady‑state energy balance and assuming negligible kinetic and potential energy changes, the heat transfer per unit mass was calculated when mass flow rates were equal. The analysis relied on comparing the temperature changes of the hot and cold streams to infer heat transfer effectiveness and system losses.

### Outcomes
The experimental outcomes showed that parallel flow produced a heat‑transfer rate of 8.78 kJ/kg, with noticeable heat loss to the surroundings indicated by unequal hot‑side and cold‑side energy changes. Counterflow operation resulted in a lower heat loss and a heat‑transfer rate of 6.27 kJ/kg, while also producing larger temperature changes in both streams—demonstrating that counterflow is more effective than parallel flow for heat exchange. In the third run, unequal pump speeds prevented calculation of heat per mass, but the temperature trends suggested that varying flow rates did not significantly reduce overall heat‑exchange effectiveness. Across all runs, the experiment successfully illustrated key thermodynamic principles, including the impact of flow configuration, the role of energy balance, and the presence of real‑world inefficiencies in practical heat‑exchange systems.

<hr>

### Images

![Heat exchanger minilab setup with containers]({{ "/assets/images/actual_images_used/heat_transfer_setup.jpeg" | relative_url }}){: .center-image style="width: 350px"}

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

![Parallel flow hand calculations diagram]({{ "/assets/images/actual_images_used/math_thermo1.JPG" | relative_url }}){: .center-image style="width: 350px"}

![Counterflow hand calculations diagram]({{ "/assets/images/actual_images_used/math_thermo2.JPG" | relative_url }}){: .center-image style="width: 350px"}

![Counterflow different speeds calculation diagram]({{ "/assets/images/actual_images_used/math_thermo3.JPG" | relative_url }}){: .center-image style="width: 350px"}