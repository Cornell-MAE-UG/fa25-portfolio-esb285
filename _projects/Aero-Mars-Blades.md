---
layout: project
title: Mars Rotorcraft Blade Design
description: Theoretical Aerodynamic Implementation and Advanced CAD
technologies: [Python, SOLIDWORKS]
image: /assets/images/actual_images_used/blade.png #change this
imagealt: 
imagecaption: 
---

## Project Overview

### Objectives

For this intro to aerodynamics class project, my team aimed to minimize the thrust required for a Mars rotorcraft blade to hover, using NASA's Ingenuity helicopter as the reference design and basis for the project.

### Process

Our team developed a Python-based aerodynamic algorithm that used a brute-force parameter sweep to explore the design space and identify the optimal blade configuration for hovering in Mars's thin atmosphere. I contributed to the optimization algorithm, helping evaluate combinations of blade twist distribution along the span, chord length, and airfoil shape, benchmarking results against Ingenuity's known specifications, to find the configuration that minimized hover thrust. Once the optimal design was identified, I used the resulting airfoil geometry and blade dimensions to generate 3D coordinate data and led the CAD modeling for the blade.

### Outcomes

I built a complete 3D CAD model of the optimized blade in SOLIDWORKS from the team's generated coordinate data. This workflow connected aerodynamic theory directly to a manufacturable design, moving from a computational parameter sweep to a finished CAD model informed by a real-world flight-proven rotorcraft. My work on the CAD modeling translated the team's analytical results into a tangible, presentable 3D design.

<hr>

### Images

![Top view of the blade]({{ "/assets/images/actual_images_used/top_view.png" | relative_url }}){: style="width: 350px"}
![Side view of the blade showing twist]({{ "/assets/images/actual_images_used/twist_1.png" | relative_url }}){: style="width: 350px"}
![Side view of the blade showing length]({{ "/assets/images/actual_images_used/blade.png" | relative_url }}){: style="width: 350px"}
