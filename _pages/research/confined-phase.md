---
layout: single
title: "Confined Phase Behavior of CO₂/Hydrocarbon Mixtures"
description: "Seyed Milad Hatamlee combines Monte Carlo simulation, workflow automation, and equation-of-state calibration to study confined CO2/hydrocarbon phase equilibrium."
permalink: /research/confined-phase/
author_profile: true
---

[← Back to Research]({{ '/research/' | relative_url }})

## Research question

How does nanoscale confinement change vapor–liquid equilibrium, and how can molecular simulation improve a compact thermodynamic model for confined mixtures?

## My contribution

- Applied Gibbs ensemble Monte Carlo (GEMC) and gauge-GCMC to study bulk and confined behavior of CO₂/n-heptane and methane/n-heptane mixtures.
- Built automated submission and post-processing workflows supporting a dataset of approximately 1,000 confined-fluid simulations.
- Diagnosed limitations of Peng–Robinson models that adjust critical properties or only the binary interaction coefficient.
- Calibrated corrections to both attraction and covolume using genetic optimization against Monte Carlo reference data.

## Principal findings

Confinement lowered bubble-point pressures, raised dew-point pressures, and narrowed the sampled two-phase envelopes. Correcting both attraction and covolume improved the description of the confined phase boundaries, reducing normalized phase-envelope RMSE by **27–61% against Monte Carlo reference data at the fitted conditions**.

The coefficients were fitted independently at selected temperatures for a **4.2 nm hydroxylated silica slit**. These results describe calibration at those conditions; interpolation, extrapolation, other pore sizes, and unseen surface chemistries were not validated.

## Methods

Towhee molecular Monte Carlo; GEMC and gauge-GCMC; thermodynamic integration and coexistence analysis; modified Peng–Robinson modeling; genetic optimization; automated simulation and data analysis.

## Simulation Snapshots

![MC snapshot]({{ '/_pages/images/slit.gif' | relative_url }})

*Representative molecular configuration of a confined fluid system obtained from Monte Carlo simulations.*

---

## Related publication

Hatamlee SM, Hoepfner M, Elmehlawy M, Lu M, Li Z, Li J. *Monte Carlo Informed Modification of Peng-Robinson Equation of State for CO₂/Hydrocarbon Mixtures Confined in Nanopores*. Accepted, Langmuir, 2026.
