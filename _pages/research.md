---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/DMF2.png"
---

My academic research can be categorized into three primary domains: 
- The conception of a programmable Electrowetting On Dielectric (EWOD)-based digital microfluidics mechanism that can manipulate sample fluids into discrete droplets, enabling automated sample preparation with minimal training. 
- The design of an electronic-based biosensor capable of detecting biomarkers with rapidity and sensitivity, for point-of-care testing. 
- COMSOL Multiphysics, which utilizes finite element analysis (FEA) to simulate the fluid convection, diffusion, surface reaction, and electric field/gradient of electronic-based biosensors, employing AC/DC, Fluid Flow, and Chemical Engineering Modules. 
 

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
