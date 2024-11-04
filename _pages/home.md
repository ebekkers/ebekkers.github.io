---
layout: about
title: 
permalink: /
subtitle: 	

profile:
  align: right
  image: avatar.jpg
  image_circular: false # crops the image to make it circular
  address: # >
#    <p>University of Amsterdam</p>
#    <p>Lab42</p>
#    <p>Amsterdam, Netherlands</p>

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

I am an assistant professor in Geometric Deep Learning in the Machine Learning Lab of the University of Amsterdam ([AMLab](https://amlab.science.uva.nl/), UvA).

Before my current position, I worked as a post-doctoral researcher in applied differential geometry at the Technical University Eindhoven (TU/e) Department of Applied Mathematics. During my PhD research at TU/e (completed cum laude in Biomedical Engineering), I focused on developing medical image analysis algorithms based on sub-Riemannian geometry in the Lie group SE(2). This work built upon the same mathematical principles that underlie models of human visual perception. I've found that these mathematical foundations are particularly valuable in machine learning, where we can leverage symmetries and geometric structure to develop robust and efficient representation learning methods.

My current research focuses on developing generalizations and efficient implementations of group equivariant architectures while expanding the application scope of the geometric deep learning paradigm.

I am honored to have received several recognitions for my work, including the MICCAI Young Scientist Award 2018 and the Philips Impact Award (MIDL 2018). I've also been fortunate to secure two personal research grants from the Dutch Research Council (NWO): a [VENI grant](https://www.nwo.nl/en/researchprogrammes/nwo-talent-programme/projects-veni/2019) on *Context-Aware Artificial Intelligence in Medical Image Analysis* and a [VIDI grant](https://www.nwo.nl/en/researchprogrammes/nwo-talent-programme/projects-vidi/vidi-2023) on *Neural Ideograms: Shaping AI with Geometry-Grounded Learning*.

# Research Vision

My research is driven by a fundamental observation: nearly all data is rooted in our physical world, and thus inherently grounded in geometry and physics. This suggests that representation learning should preserve this grounding to remain meaningful. For example, preserving group transformation laws and symmetries through equivariant layers is crucial in domains such as computational physics, chemistry, robotics, and medical imaging, and leads to effective and generalizable architectures and improved data efficiency. Similarly, in generative models applied to non-Euclidean data spaces, maintaining the manifold structure is essential in order to obtain meaningful samples.

This vision centers on the principle of grounding in geometry:

> A representation, method, or theory is grounded in geometry if it can be amenable to geometric reasoning, that is, it abides by the mathematics of geometry and physics.


Recently, our group took the lead in organizing the [ICML'24 GRaM workshop](https://gram-workshop.github.io/) on Geometry-Grounded Representation Learning and Generative Modeling (GRaM) to bring together researchers working on this vision. Our work focuses on several key areas:

* **Structure-preserving learning**
  * **Preservation of symmetries**: E.g., through equivariant operators.
  * **Dynamical systems on manifolds**: Representation learning and generative modeling using ordinary, stochastic, and differential equations (ODEs, SDEs, PDEs) on manifolds.
  * **Computing with geometric representations**: Such as the processing of multi-vectors using geometric algebra, steerable vectors using Clebsch-Gordan products, and hyperbolic features using Fréchet means.
* **Structure-inducing learning**
  * **Self-supervised learning**: E.g., learning to embed data in geometric latent spaces through (geodesic) distance-based similarity metrics.
  * **Geometric priors**: E.g., soft constraints on model weights.
  * **Physics-Informed Neural Networks**: E.g., inducing the structure of established physical and geometric laws into neural networks through dedicated losses.
* **Generative modeling and density estimation**
  * **Geometric latent variable models**: I.e., the use of latent variables that live in a manifold.
  * **New Methods**: And adaptations of methods capable of:
  * **Generating geometric objects**: E.g., generating atomic point clouds or shapes.
  * **Generating fields over manifolds**: E.g., generating vector fields or spherical signals.
* **Grounding in theory**
  * **Theoretical frameworks**: Unifying analyses and formulations that provide a generalizing perspective on deep learning paradigms.
  * **Open problems**: Identifying and addressing unresolved questions and challenges that lie at the intersection of geometry and learning

