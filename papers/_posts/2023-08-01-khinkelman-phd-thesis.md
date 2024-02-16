---
layout: paper
title: "Modelica modeling and ecosystem biomimicry of district energy systems"
year: "2023"
shortref: "Hinkelman <i>Pennsylvania State University</i> 2023"
nickname: hinkelman-phd-thesis
journal: "Pennsylvania State University"
authors: "Kathryn Hinkelman"
image: /assets/images/papers/2023-ies-hinkelman-phd-thesis.png
redirect_from: 
fulltext: "https://etda.libraries.psu.edu/catalog/27446kgh5244"
pdflink: "https://www.researchgate.net/publication/374229997_Modelica_Modeling_and_Ecosystem_Biomimicry_of_District_Energy_Systems"
# github: 
doi: 
category: paper
projects_handle: biceps, doe-des
# Note: 'published' is a Jekyll keyword and does not refer to whether the paper is published, but rather to whether this Markdown should be part of the rendered site.
published: true
preprint: false
embargo: false	
peerreview: false
review: false
tags: [biomimicry, building systems, design, district energy, district heating, district cooling, dynamical systems, ecological network analysis, ecosystem biomimicry, exergy, modelica, modeling and simulation, numerical performance, optimization, steam, sustainability, systems]
---
{% include JB/setup %}

<div class="bigspacer"></div>
<div class="head">Abstract</div>
<div class="spacer"></div>

By integrating multiple energy systems at a community level, it is possible to use local 
renewable energy supplies and share energy resources between various producers, consumers, 
and storages. For heating and cooling needs, this integration occurs through district energy 
systems (DES), which can capture waste heat, allow multiple buildings to share thermal energy 
resources, and provide renewable energy conversion and resource sharing opportunities. However, 
before industry practitioners can leverage DES benefits for communities and cities, we need to 
address critical gaps in both the foundational energy modeling tools and the whole-system design approach. 
As such, the objective of this work is to enable district heating and cooling as linkages with waste-heat 
recovery potential for integrated energy systems. To meet this objective, this dissertation 
presents several projects on the comprehensive design of DES and their controls, which are made 
possible through advancements in Modelica modeling and novel engineering applications of ecosystem 
biomimicry. 

To address fundamental gaps in modeling software and methods for complete DES 
simulation, this dissertation first focused on existing district cooling (DC) and steam-based 
district heating (DH) systems. For DC systems, we developed a methodology for DC model-based 
retrofits, released new open-source DC models in the Modelica Buildings Library, and leveraged these 
models for a real-world case study at the University of Colorado Boulder. Multi-dimensional analysis 
of the validated model led to several energy saving strategies, including control setpoint optimization, 
equipment modification, and pump setpoint adjustments. Results indicated that a combination of the 
studied measures can save the campus annually 84.6 MWh of energy, 8.9% of electricity costs, 58.0 metric 
tons of carbon dioxide emissions, while the waterside economizer cuts down chillers' run times by 
201 days/year, reducing maintenance costs and extending chiller life. 

For steam-based DH systems, this work improved the performance of water/steam thermodynamic calculations for 
heating applications, released numerous DH models in the Modelica Buildings Library, and evaluated the accuracy and 
numerical performance of our new modeling approach from fluid mediums to complete districts. We improved the numerical 
performance of water/steam thermodynamic calculations by coupling a numerically efficient liquid water model 
(that represents enthalpy as a function of temperature only) with an industrial water/steam model (i.e., IAPWS IF97). 
Through this “split-medium” approach, we broke costly algebraic loops in the problem formulation by decoupling mass 
and energy balance equations. Compared to district models with the commonly adopted IF97 water/steam model for all 
phase regions, the new implementation improves the scaling rate for large districts from cubic to quadratic with 
negligible compromise to accuracy. For an annual simulation with 180 buildings, this translates to a computing time 
reduction from 33 to 1-1.5 hours. These results are critically important for industry practitioners to simulate 
steam DH systems at large scales. 

To address the need for whole-system design approaches for integrated energy systems, we proposed an 
innovative ecosystem biomimicry approach. This approach functionally analyzes biological systems, abstracts 
those functions into models, and translates the models to create new technologies. Because ecosystem biomimicry is an 
emerging yet promising field, this dissertation includes an interdisciplinary literature review to synthesize trends 
across case studies, evaluate design methodologies, and identify future opportunities when applying ecosystem 
biomimicry to engineering practices, including cyber, physical, and cyber-physical systems. Through 
bibliographic analysis, statistical analysis, and deep dives into engineering applications and design 
methodologies, we synthesized trends in ecosystem biomimicry and identified opportunity spaces. For future 
studies, this review provides a comprehensive reference for ecosystem biomimetic design practices and a
pplication opportunities across multiple engineering domains. 

Following the critical review on ecosystem 
biomimicry, we then pursued case studies for district-level integrated energy systems. Ecological network 
analysis (ENA) was identified from the review as a promising whole-system analysis methods for cyber-physical 
systems that had not yet been applied for complex dynamic engineering systems. To fill this gap, this work 
first translated ENA from biological sciences for engineering applications. Then, we demonstrated the novel 
ENA method to design the heating and cooling systems for an office building and data center, coupling the 
buildings together via ambient-loop district energy. For the models to suit integrated building energy systems, 
which have multiple energy types and non-negligible dynamics, we were the first to formulate ENA (1) on an 
exergy basis and (2) dynamically for non-biological applications. For a case study that iteratively redesigned 
building heating and cooling systems, the proposed approach reduced source energy by 15% and HVAC site energy 
by 84% with negligible sacrifice to thermal comfort. Counter-intuitively, the redesign also reduced the exergy 
efficiency of the total system from 60% to 34%. This indicates that ENA and other network metrics that classify 
system organization can outperform traditional efficiency-based metrics for integrated energy systems.


<div class="bigspacer"></div>
<div class="head">BibTeX Citation</div>
<div class="spacer"></div>

```
@phdthesis{hinkelman2023modelica,
  title={Modelica Modeling and Ecosystem Biomimicry of District Energy Systems},
  author={Hinkelman, Kathryn},
  year={2023},
  school={The Pennsylvania State University}
}
```
