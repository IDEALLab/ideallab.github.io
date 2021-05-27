---
layout: paper
title: "Potential Energy Surfaces for Analysis and Conceptual Design and Analysis of Mechanical Systems"
year: "2021"
shortref: "Manion and Fuge 2021"
nickname: potential-energy-surf
journal: "Proceedings of the ASME 2021 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference (IDETC/CIE2021)"
volume:
issue:
pages:
authors:"Charles A. Manion, Mark Fuge"
image: /assets/images/papers/2021_manion_potential_surf.png
redirect_from:
fulltext:
pdf: /assets/pdfs/2021_manion_potential_energy_surfaces_idetc.pdf
pdflink:
github:
doi:
category: paper
published: true
tags: [conceptual design, design automation, mechanism design, computational design synthesis, differentiable simulation, potential energy surfaces]
---

{% include JB/setup %}

# Abstract
Current computational Design Synthesis approaches have had trouble generating components with higher kinematic pairs and have instead relied on libraries of predefined components. However, higher kinematic pairs are ubiquitous in many mechanical devices such as ratchets, latches, locks, trigger mechanisms, clock escapements, and materials handling systems. In many cases there is a need to synthesize new higher kinematic pair devices.

To address this problem, we develop a new representation for mechanical systems that extends the capabilities of configuration spaces to consider arbitrary energy storing mechanical devices. The key idea underlying this representation is the use of potential energy surfaces as a generalization of configuration spaces. This generalization enables modelling of mechanical systems in a physics independent manner and captures behaviors such as dynamics.

By modeling a device through the lens of a potential energy surface, we demonstrate that differentiable simulation is possible. Differentiable simulation enables efficient calculation of gradients of potential energy surface parameters with respect to an objective function that depends on trajectories taken on the potential energy surface. This allows synthesis of mechanical devices with desired kinematic and dynamic behavior through gradient descent. We demonstrate this through several synthesis examples including positioning devices (e.g., a funnel) and timing devices (e.g., an oscillator).

# BibTeX Citation

```
@proceedings{manion2021PotentialEnergySurfaces,
  title={Potential Energy Surfaces for Analysis and Conceptual Design and Analysis of Mechanical Systems},
  author={Manion, Charles A and Fuge, Mark},
  booktitle={ASME 2021 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference},
  year={2021},
  organization={American Society of Mechanical Engineers Digital Collection}
}
```