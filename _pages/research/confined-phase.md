---
layout: single
title: "Confined Phase Behavior of CO₂/Hydrocarbon Mixtures"
permalink: /research/confined-phase/
author_profile: true
---
[← Back to Research]({{ '/research/' | relative_url }})

## Overview

This project focuses on understanding phase behavior of CO₂ and hydrocarbon mixtures under nanoscale confinement using molecular simulation and thermodynamic modeling. Confinement significantly alters phase equilibrium compared to bulk systems, which has important implications for subsurface energy systems, carbon storage, and hydrocarbon recovery.

---

## Motivation

Accurate prediction of phase behavior in nanoporous environments remains a major challenge in thermodynamics. Classical equations of state (EoS), developed for bulk systems, often fail to capture confinement-induced effects such as shifted critical properties, altered phase boundaries, and enhanced adsorption.

This work aims to bridge this gap by combining molecular simulations with modified thermodynamic models.

---

## Approach

- Monte Carlo simulations:
  - Grand Canonical Monte Carlo (GCMC)  
  - Gibbs Ensemble Monte Carlo (GEMC)  

- Modeling of binary mixtures:
  - CO₂ / hydrocarbon systems  
  - Phase equilibrium under confinement  

- Development of modified equations of state:
  - Extension of Peng–Robinson EoS  
  - Incorporation of confinement effects through parameter adjustment  

---

## Research Focus

- Investigating how confinement alters vapor–liquid equilibrium (VLE)  
- Studying shifts in phase boundaries and critical behavior  
- Evaluating the limitations of classical EoS under nanoscale conditions  
- Developing improved predictive models for confined systems  

---

## Simulation Snapshots

<div class="phase-comparison">
  <div class="phase-comparison__frame" style="--canvas-height: 134.9746%; --channel-x: -49.6875%; --channel-y: -50.1%;">
    <img src="{{ '/_pages/images/slit.gif' | relative_url }}" alt="Monte Carlo animation of fluid confined in a slit pore" width="800" height="500">
  </div>
  <div class="phase-comparison__frame" style="--canvas-height: 107.6658%; --channel-x: -55.4375%; --channel-y: -49.4%;">
    <img src="{{ '/_pages/images/circ.gif' | relative_url }}" alt="Monte Carlo animation of fluid confined in a cylindrical pore" width="800" height="500">
  </div>
</div>


*Representative molecular configuration of a confined fluid system obtained from Monte Carlo simulations.*

---

## Related publication

Hatamlee SM, Hoepfner M, Elmehlawy M, Lu M, Li Z, Li J. *Monte Carlo Informed Modification of Peng-Robinson Equation of State for CO₂/Hydrocarbon Mixtures Confined in Nanopores*. Accepted, Langmuir, 2026.

The equation-of-state parameters were fitted at sampled temperatures; interpolation and extrapolation beyond those conditions were not validated.
