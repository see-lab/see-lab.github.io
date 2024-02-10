---
layout: paper
title: "A fast and accurate modeling approach for water and steam thermodynamics with practical applications in district heating system simulation"
year: "2022"
shortref: "Hinkelman et al. <i>Energy</i> 2022"
nickname: steam-dh
journal: "Energy"
volume: "254"
issue: "A"
pages: "124227"
authors: "Kathryn Hinkelman, Saranya Anbarasu, Michael Wetter, Antoine Gautier, Wangda Zuo"
image: /assets/images/papers/2023-steam-computing-speed.png
redirect_from: 
fulltext: "http://dx.doi.org/10.1016/j.energy.2022.124227"
pdflink: "https://www.researchgate.net/publication/360652395_A_fast_and_accurate_modeling_approach_for_water_and_steam_thermodynamics_with_practical_applications_in_district_heating_system_simulation"
github:  "https://github.com/lbl-srg/modelica-buildings/releases/tag/v10.0.0"
doi: 10.1016/j.energy.2022.124227
category: paper
# Note: 'published' is a Jekyll keyword and does not refer to whether the paper is published, but rather to whether this Markdown should be part of the rendered site.
published: true
preprint: false
embargo: false	
peerreview: true
review: false
tags: [steam, district heating, computing speed, modeling and simulation, modelica]
---
{% include JB/setup %}

# Abstract 

In U.S. district heating (DH) systems, steam is the most common heat transport medium. 
Industry demand for new advanced modeling capabilities of complete steam DH systems is 
increasing; however, the existing models for water/steam thermodynamics are too slow for 
large system simulations because of computationally expensive algebraic loops that require 
the solution to nonlinear systems of equations. For practical applications, this work 
presents a novel split-medium approach that implements numerically efficient liquid water 
models alongside various water/steam models, breaking costly algebraic loops by decoupling 
mass and energy balance equations. New component models for steam DH systems are also 
presented. We implemented the models in the equation based Modelica language and evaluated 
accuracy and computing speed across multiple scales: from fundamental thermodynamic 
properties to complete districts featuring 10 to 200 buildings. Compared to district models 
with the IF97 water/steam model and equipment models from the Modelica Standard Library, the 
new implementation improves the scaling rate for large districts from cubic to quadratic 
with negligible compromise to accuracy. For an annual simulation with 180 buildings, this 
translates to a computing time reduction from 33 to 1–1.5 h. These results are critically 
important for industry practitioners to simulate steam DH systems at large scales.

# BibTeX Citation

```
@article{HINKELMAN2022124227,
title = {A fast and accurate modeling approach for water and steam thermodynamics with practical applications in district heating system simulation},
journal = {Energy},
volume = {254},
pages = {124227},
year = {2022},
issn = {0360-5442},
doi = {https://doi.org/10.1016/j.energy.2022.124227},
author = {Kathryn Hinkelman and Saranya Anbarasu and Michael Wetter and Antoine Gautier and Wangda Zuo},
}
```
