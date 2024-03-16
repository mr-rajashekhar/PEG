---
layout: post
category: research_area
title: "Modular Multilevel Converters"
image: assets/images/Hbridge.png
---

Cascaded H-bridge (CHB) based electric vehicle
chargers are widely recognized for their modularity, scalability,
and robust fault-tolerant capability. Such converters are often
modulated using level-shifted carrier-based PWM (LSPWM)
schemes due to computational simplicity and ease of implemen-
tation, but results in significant power imbalance among the
modules. This power imbalance can be mitigated by reassigning
carriers to modules, called Carrier-Reassignment PWM (CR-
PWM). A First-In-First-Out (FIFO) based CRPWM is very easy
to implement and provides some improvement over LSPWM,
but fails to achieve perfect power balance. This paper proposes
a novel carrier-reassignment scheme specifically designed for a
17-level CHB stage with eight reassignments per fundamental
cycle, resulting in near-perfect power balance among modules.
The redistribution of power also results in improvements in
semiconductor losses - both conduction and switching loss. Loss
models for the semiconductor devices were created through
hardware double-pulse tests, SPICE and PLECS models, and
integrated with MATLAB/Simulink to validate the proposed
PWM scheme.
