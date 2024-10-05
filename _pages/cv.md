---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Full CV can be found [here](https://aiftakher.github.io/files/1.1_Ashfaq_CV.pdf). (Update: 10/5/2024)


Education
======
* Ph.D. in Chemical Engineering, Texas A&M University, 2025 (expected)
* M.Sc. in Chemical Engineering, Bangladesh University of Engineering and Technology, 2020
* B.Sc. in Chemical Engineering, Bangladesh University of Engineering and Technology, 2018

Research Experinece
======
* Multiscale modeling, machine learning, high-throughput screening, and process optimization
  * Performing computer-aided molecular and process design for ionic liquid-based selective separation of azeotropic refrigerant mixtures. Developed neural net models for regression and classification of complex ionic-liquid properties.
  * Discovered new ionic liquids and process configurations by high-throughput screening of over 340000 molecules and rigorous process optimization, resulting in 48% reduction in energy consumption and 27% reduction in CO2 emissions.
  * Supervisor: M. M. Faruque Hasan
 
* Optimization theory and algorithms 
  * Proposed new reformulations and encodings of constrained mixed-integer nonlinear programs into equivalent quadratic unconstrained binary optimization (QUBO) programs, thereby allowing direct solutions using quantum annealing.   
  * Lead developer of interval arithmetic embedded automatic differentiation package that computes minima and Hessian bounds of arbitrary second-order continuous functions, thereby providing tight convex and edge-concave relaxations.
  * Supervisor: M. M. Faruque Hasan

* Surrogate optimization and data science 
  * Proposed a hybrid optimization algorithm with local optimality guarantee that integrates multiple fidelity models for efficient process optimization. Demonstrated computational tractability of the algorithm in a case study where Bayesian optimization was performed on the equilibrium model (low fidelity) while the rate-based model (high fidelity) was used for sampling and validation.   
  * Topological analysis of high dimensional space using Euler Characteristic, Wasserstein distance, and Cosine similarity. 
  * Supervisor: M. M. Faruque Hasan

  


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
