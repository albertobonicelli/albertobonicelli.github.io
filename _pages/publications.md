---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My area of research encompasses mathematical quantum field theory, microlocal analysis and stochastic partial differential equations. I study how these topics talk to each other at the interface of analysis, probability and algebra.

## Research interests
* Singular stochastic PDEs
* Algebraic quantum field theory
* Algebraic and analytic aspects of renormalization
* Microlocal analysis
* path integral formulation of SDEs

## Papers
* **On the stochastic Sine-Gordon model: an interacting field theory approach** <br>
  A.B., Claudio Dappiaggi, Paolo Rinaldi  <br>
   	[arXiv:2311.01558 [math-ph]](https://arxiv.org/pdf/2311.01558.pdf)
  
* **A microlocal investigation of stochastic partial differential equations for spinors with an application to the Thirring model** <br>
  A.B., Beatrice Costeri, Claudio Dappiaggi, Paolo Rinaldi  <br>
   	[arXiv:2309.16376 [math-ph]](https://arxiv.org/pdf/2309.16376.pdf)

* **An algebraic correspondence between stochastic differential equations and the Martin-Siggia-Rose formalism** <br>
  A.B., Claudio Dappiaggi, Nicolò Drago  <br>
   	Mathematical Physics, Analysis and Geometry 27 (3), 1-52 [DOI](https://doi.org/10.1007/s11040-024-09488-7)

* **An Algebraic and Microlocal Approach to the Stochastic Nonlinear Schrödinger Equation** <br>
  A.B., Claudio Dappiaggi, Paolo Rinaldi  <br>
  Annales Henri Poincaré 	24, 2443–2482 (2023) [DOI]([https://arxiv.org/pdf/2311.01558.pdf](https://doi.org/10.1007/s00023-023-01291-4))

## Collaborators
* **[Claudio Dappiaggi](https://claudiodappiaggi.com/)**, University of Pavia <br>
* **[Nicolò Drago](https://nicolodrago.wixsite.com/mysite)**, University of Trento <br>
* **[Paolo Rinaldi](https://www.paolorinaldi.net/)**, University of Bonn <br>
* **[Lorenzo Zambotti](https://www.lpsm.paris/users/zambotti/index)**, Sorbonne Université, LPSM <br>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
