---
layout: about
title: home
permalink: /
subtitle: 

profile:
  align: right
  image: ErikBekkers.jpg
  address: # >
#     <p>University of Amsterdam</p>
#     <p>Science Park 904</p>
#     <p>1098 XH Amsterdam</p>
#     <p>The Netherlands</p>

news: false  # includes a list of news items
recent_papers: false
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

Erik Bekkers is an assistant professor in **Geometric Deep Learning** in the Machine Learning Lab of the University of Amsterdam (AMLab, UvA). Before this he did a post-doc in applied differential geometry at the dept. of Applied Mathematics at Technical University Eindhoven (TU/e). In his PhD thesis (cum laude, Biomedical Engineering, TU/e), he developed medical image analysis algorithms based on sub-Riemannian geometry in the Lie group SE(2) using the same mathematical principles that underlie mathematical models of human visual perception. Such mathematics find their application in machine learning where through symmetries and geometric structure, robust and efficient representation learning methods are obtained. His current work is on generalizations of group convolutional NNs, improvements of their computational and representation efficiency through sparse (graphs) and adaptive learning mechanisms. Erik is a recipient of a MICCAI Young Scientist Award 2018, Philips Impact Award (MIDL 2018) and a personal VENI research grant (awarded by the Dutch Research Council (NWO)).

**Research topics**

* Group equivariant deep learning
* Leveraging geometry in (graph) neural networks
* Computing with geometric quantities (manifold-valued features)
* Geometric latent space modeling

**Team**

* David Romero 
* Putri van der Linden
* Rob Hesselink 
* Sharvaree Vadgama 
* Michel Botros

<div class="projects">
<div class="grid">
{%- assign categorized_people = site.people | where: "category", "PhD Students" -%}
{%- assign ordered_people = categorized_people | group_by: "order" -%}
{%- assign ordered_people = ordered_people | sort: "name" -%}
{%- for o in ordered_people -%}
{%- assign sorted_people = o.items | sort_natural: "last_name" -%}  
<!-- Generate cards for each person -->
  {%- for person in sorted_people -%}
    {% include person_card_small.html %}
  {%- endfor %}
{%- endfor -%}
</div>
</div>
