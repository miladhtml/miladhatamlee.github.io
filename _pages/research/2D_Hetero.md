---
layout: single
title: "Interfacial Heat Transfer in 2D Heterostructures"
description: "Seyed Milad Hatamlee combines NEMD, GULP lattice dynamics, and vibrational-mode analysis to explain thermal conductance across 15 two-dimensional interfaces."
permalink: /research/2D_Hetero/
author_profile: true
---

[← Back to Research]({{ '/research/' | relative_url }})

## Research question

Which vibrational features explain differences in thermal conductance across two-dimensional material interfaces?

## My contribution

- Computed interfacial thermal conductance across **15 lateral interfaces** between carbon-based two-dimensional materials using non-equilibrium molecular dynamics.
- Combined the heat-transfer simulations with GULP lattice-dynamics calculations.
- Analyzed the spatial distribution of vibrational eigenvectors to classify modes and quantify localization near interfaces.
- Compared interfacial-mode populations with bulk phonon density-of-states overlap and evaluated empirical conductance correlations.

## Principal findings

Within the studied interface set, bulk density-of-states overlap did not provide a useful overall correlation with conductance. A larger population of localized interfacial modes correlated with lower conductance, making interface-specific vibrational analysis a more informative descriptor.

The regression describes the investigated dataset; it is not an independently validated predictor for arbitrary interfaces.

## Methods

LAMMPS NEMD; GULP lattice dynamics; Python eigenvector processing and mode classification; density-of-states analysis; finite-size and sensitivity checks; regression-based descriptor analysis.

## Simulation setup and results

<figure style="display: block; text-align: center;">
  <img src="{{ '/_pages/images/Figs_inter.png' | relative_url }}" alt="Simulation cell with hot and cold thermal baths, fixed atoms at the ends, and a heterostructure interface." class="align-center" style="width: auto;">
  <figcaption>Non-equilibrium molecular dynamics setup for interfacial heat transfer, showing the hot and cold baths, fixed end regions, and heterostructure interface.</figcaption>
</figure>


![Carbon-based interfaces]({{ '/_pages/images/fig_hetero.png' | relative_url }})


## Related publication

Hatam-Lee SM, Gordiz K, Rajabpour A. *Lattice-dynamics-based descriptors for interfacial heat transfer across two-dimensional carbon-based nanostructures*. Journal of Applied Physics, 2021.
