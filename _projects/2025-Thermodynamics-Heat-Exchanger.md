---
layout: project
title: Heat Exchanger Analysis
description: Analysis of Heat Exchanger for Thermodynamic Course
technologies: [MATLAB, Lab Equipment]
image: /assets/images/actual_images_used/IMG_2759.jpeg
imagealt: Heat exchanger minilab experimental setup
imagecaption: Minilab Heat Exchanger System Setup
---

## Project Overview

### Objectives

### Process

### Outcomes

% add a line 

### Images

For my thermodynamics course, I was tasked with analyzing a thermodynamics system in the real world using thermodynamic concepts. A minilab with a heat exchanger was done for this project. 

## Set Up of Mini-lab

The set up contained four containers: one with hot (red) water, one with cold (blue) water, and two empty containers. The hot water was heated using heat pump and the cold water was cooled using ice. The containers were connected with tubes and a heat exchanger that allowed the hot and cold fluids to exchange heat.

Below is an image of the initial set up with the heat exchanger:

![Heat exchanger minilab setup with containers]({{ "/assets/images/actual_images_used/IMG_2755.jpeg" | relative_url }}){: .center-image style="width: 500px"}

## Experimental Data Collection

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

## Run 1: Parallel Flow Analysis

The first run was done with parallel flow with the pumps running at the same speed of +1. The speed of the water flow was not obtained in this experiment. 

Using the following analysis, the heat per mass output can be calculated, assuming steady state, no work done and negligible changes in kinetic and potential energies. The steady state assumption is valid because the temperatures reached a plateau after a sufficient amount of time.

![Parallel flow hand calculations diagram]({{ "/assets/images/actual_images_used/IMG_2330.JPG" | relative_url }}){: .center-image style="width: 500px"}

As shown the heat per mass output is 8.78 kJ/kg. This run shows that there is heat being lost to the surroundings and that it is not a perfectly closed system as well as not adiabatic. This is observed by the fact that the heat lost by the hot water is not equal to the heat gained by the cold water.

## Run 2: Counterflow Analysis

For the second run, the heat exchanger was run in counterflow with the pumps running at the same speed of +1. 

The same assumptions from run 1 were used in the analysis of the data as shown below. 

![Counterflow hand calculations diagram]({{ "/assets/images/actual_images_used/IMG_2331.JPG" | relative_url }}){: .center-image style="width: 500px"}

The heat per mass output for run 2 was 6.27 kJ/kg. This run has a smaller heat loss compared to run 1 and the change in temperatures of both waters is higher in run 2 than it was in run 1, which suggests that counterflow is more effective at exchanging heat compared to parallel flow.

## Run 3: Counterflow with Different Flow Speeds

For the third run, the heat exchanger was run in counterflow with the pumps running at different speeds: the hot water running at -1 and the cold running at +1. Again, the water flow was not determined in this experiment. 

The same assumptions except about the mass flow were used in analysing run 3. 

![Counterflow different speeds calculation diagram]({{ "/assets/images/actual_images_used/IMG_2332.JPG" | relative_url }}){: .center-image style="width: 500px"}

As shown, the heat per mass output can not be determined from the data collected, due to the mass flows of the waters being different. However, if the heat per mass output is assumed to be within a similar range as run 2, it can be inferred that the effectiveness of heat exchange does not significantly change with different pump speeds.

## Discussion

From data, the counterflow seems to be more effective in changing the temperatures of the water. Also, having different speeds seems to lead to larger differences in changes in temperature between the hot and cold water streams. Overall, this experiment successfully demonstrated key thermodynamic principles including heat transfer, energy balance, and the advantages of different heat exchanger configurations.
