---
layout: paper
title: "Modelica-based modeling and simulation of district cooling systems: A case study"
year: "2022"
shortref: "Hinkelman et al. <i>Applied Energy</i> 2022"
nickname: district-cooling
journal: "Applied Energy"
volume: "311"
issue: 
pages: "118654"
authors: "Kathryn Hinkelman, Jing Wang, Wangda Zuo, Antoine Gautier, Michael Wetter, Chengliang Fan, Nicholas Long"
image: /assets/images/papers/2022_khinkelman_district-cooling.jpg
redirect_from: 
fulltext: "https://doi.org/10.1016/j.apenergy.2022.118654"
pdflink: "https://www.researchgate.net/publication/358570363_Modelica-based_modeling_and_simulation_of_district_cooling_systems_A_case_study"
github:  "https://github.com/lbl-srg/modelica-buildings/releases/tag/v8.1.0"
doi: 10.1016/j.apenergy.2022.118654
category: paper
# Note: 'published' is a Jekyll keyword and does not refer to whether the paper is published, but rather to whether this Markdown should be part of the rendered site.
published: true
preprint: false
embargo: false	
peerreview: true
review: false
tags: [district cooling, modelica, modeling and simulation, waterside economizer, optimization, case study]
---
{% include JB/setup %}

# Abstract 

While equation-based object-oriented modeling language Modelica can evaluate practical energy 
improvements for district cooling systems, few have adopted Modelica for this type of large-scale 
thermo-fluid system. Further, to our best knowledge, district cooling modeling studies have yet 
to include hydraulics in piping networks alongside plant models featuring realistic mechanical 
systems and controls. These are critical details to include when looking to make energy and 
control improvements in many physical system installations. To fill these gaps, this study 
released new open-source district cooling models at the Modelica Buildings Library and leveraged 
these models for a real-world case study at the University of Colorado Boulder. The site includes 
six buildings connected to a central chiller plant featuring a waterside economizer. Several 
energy saving strategies are pursued based on the validated model, including control setpoint 
optimization, equipment modification, and pump setpoint adjustments. Results indicate that a 
combination of the studied measures can save the campus annually 84.6 MWh of energy, 8.9% of 
electricity costs, 58.0 metric tons of carbon dioxide emissions, while the waterside economizer 
cuts down chillers’ run times by 201 days/year, reducing maintenance costs and extending chiller life.

# BibTeX Citation

```
@article{Hinkelman2022118654,
title = {Modelica-based modeling and simulation of district cooling systems: A case study},
journal = {Applied Energy},
volume = {311},
pages = {118654},
year = {2022},
issn = {0306-2619},
doi = {https://doi.org/10.1016/j.apenergy.2022.118654},
author = {Kathryn Hinkelman and Jing Wang and Wangda Zuo and Antoine Gautier and Michael Wetter and Chengliang Fan and Nicholas Long},
}
```
