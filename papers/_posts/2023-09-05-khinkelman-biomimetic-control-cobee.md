---
layout: paper
title: "Ecosystem-Level Biomimicry for the Built Environment: Adopting Systems Ecology Principles for the Control of Heterogeneous Energy Systems"
year: "2023"
shortref: "Hinkelman et al. <i>COBEE Conference</i> 2023"
nickname: biomimetic-control-cobee
journal: "The 5th International Conference on Building Energy and Environment"
volume: 
issue: 
pages: "2663--2676"
authors: "Kathryn Hinkelman, Wangda Zuo, Jing Wang, Sen Huang, and Michael Wetter"
image: /assets/images/papers/2023-cobee-bps-control.png
redirect_from: 
fulltext: "http://dx.doi.org/10.1007/978-981-19-9822-5_284"
pdflink: "https://www.researchgate.net/publication/373664178_Ecosystem-Level_Biomimicry_for_the_Built_Environment_Adopting_Systems_Ecology_Principles_for_the_Control_of_Heterogeneous_Energy_Systems"
github: 
doi: 10.1007/978-981-19-9822-5_284
category: paper
# Note: 'published' is a Jekyll keyword and does not refer to whether the paper is published, but rather to whether this Markdown should be part of the rendered site.
published: true
preprint: false
embargo: false	
peerreview: true
review: false
tags: [biomimicry, building controls, interconnected energy systems, modelica, resiliency]
---
{% include JB/setup %}

# Abstract 

This paper presents, to our knowledge, the first system-level engineering study to bio-mimic the 
cybernetics and flow dynamics of energy resources in natural ecosystems for the control of heterogeneous 
energy infrastructures in the built environment. To this end, we introduce a novel Biomimetic Pulsing 
State (BPS) control that functionally mimics mature ecosystems. A preliminary Modelica-based case study 
features a single-family residential building with electrical and HVAC subsystems. The BPS control 
objective is to minimize the energy exchange between the building and the grid for the purposes of 
future self-supporting buildings and grid stability. The building contains PV, a wind turbine, a 
battery storage system, and a fan coil/heat pump HVAC system served by an ambient district energy 
network. Evaluating the control performance (BPS vs. constant setpoint) over several renewable energy 
scenarios (net importer, net zero, net exporter), simulation results show how the building's HVAC 
system can dynamically adjust its electrical load and temperatures to the electrical system's net 
energy status in real-time with BPS control. As a net importer, the heat pump consumed 29% less 
energy and its peak power reduced by 15% with BPS control compared to the constant setpoint case, 
with the zone air temperature 1C lower on average. As a net exporter, the heat pump effectively 
consumed the same energy, but the peak power increased by 34% with BPS control, while the zone air 
temperature was 1C higher when renewable energy was abundant, preheating the home. BPS and constant 
setpoint control produced comparable results under a net zero scenario. While further evaluation is 
essential, BPS control may help communities meet their sustainability and resiliency targets as they 
transition towards fully distributed and renewable energy grids.


# BibTeX Citation

```
@inproceedings{Hinkelman2023COBEE,
	address = {Montreal, QC, Canada},
	author = {Hinkelman, Kathryn and Zuo, Wangda and Wang, Jing and Huang, Sen and Wetter, Michael},
	booktitle = {The 5th International Conference on Building Energy and Environment (COBEE)},
	doi = {10.1007/978-981-19-9822-5_284},
	pages = {2663--2676},
	title = {Ecosystem-Level Biomimicry for the Built Environment: Adopting Systems Ecology Principles for the Control of Heterogeneous Energy Systems},
	year = {2023}
}
```
