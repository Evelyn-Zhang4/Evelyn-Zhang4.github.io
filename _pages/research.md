---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/DMF2.png"
---

My academic research can be categorized into four sections: 
- The conception of a programmable Electrowetting On Dielectric (EWOD)-based digital microfluidics mechanism that can manipulate sample fluids into discrete droplets, enabling automated sample preparation and detection with minimal training hand. 
- Nanopore-based sensing schemes are combined with peptide nucleic acid (PNA) conjugated beads assay to achieve sequence-specific detection of nucleic acids, enabling early cancer detection in a cost-effective and rapid manner.
- The design of electronic-based biosensors capable of detecting biomarkers including proteins and cells with rapidity and sensitivity, for point-of-care testing. 
- COMSOL Multiphysics employs finite element analysis (FEA) to simulate fluid convection, diffusion, surface reactions, and the electric field/gradient in electronic-based biosensors, utilizing the AC/DC, Fluid Flow, and Chemical Engineering Modules.
 

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
