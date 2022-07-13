---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
---
* Current employment (Dec 2019)
	* Role: Assistant Professor
	* Employer: Amsterdam Machine Learning Lab (AMLab), University of Amsterdam
* Sep 2016 -- Dec 2019
	* Role: Post-doc 
	* Employer: Centre for Analysis, Scientific Computing and Applications (CASA), Dept of Applied Mathematics and Computer Science, Eindhoven University of Technology
* Jan 2013 -- Sep 2016
	* Role: PhD-candidate
	* Employer: Dept of Biomedical Engineering, Eindhoven University of Technology

Education
---
* PhD (Cum Laude) in Medical/Mathematical Image Analysis, Eindhoven University of Technology (2017)
* MSc in Biomedical Engineering, Eindhoven University of Technology (2012)
* BSc in Biomedical Engineering, Eindhoven University of Technology (2009)

Awards
---
* Young Scientist Award awarded by the Medical Image Computing and Computer Assisted Interventions (MICCAI) society in 2018
* Philips Impact Award awarded at the international conference on Medical Imaging with Deep Learning (MIDL) 2018
* Nominated for TU/e best Ph.D. Thesis Award 2018
* Cum Laude for my Ph.D. thesis


Publications
---

Preprints / Under Review
---
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'preprint' %}
      <li> {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>


Journal Articles
---
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
     <li> {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>

Refereed Conference/Workshop Papers
---
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %}
  <li>    {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>

Monographs
---
<ol>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'thesis' %}
   <li>   {% include archive-single.html %} </li>
  {% endif %}
{% endfor %}
</ol>

