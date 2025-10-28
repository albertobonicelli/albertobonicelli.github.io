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

## Publications
  
* **On the stochastic Sine-Gordon model: an interacting field theory approach** <br>
  A.B., Claudio Dappiaggi, Paolo Rinaldi  <br>
   	Communications in Mathematical Physics  405, 288 (2024) [DOI](https://doi.org/10.1007/s00220-024-05165-6)
  
* **A microlocal investigation of stochastic partial differential equations for spinors with an application to the Thirring model** <br>
  A.B., Beatrice Costeri, Claudio Dappiaggi, Paolo Rinaldi  <br>
   	Mathematical Physics, Analysis and Geometry 27 (3), 1-52 [DOI](https://doi.org/10.1007/s11040-024-09488-7)

* **An algebraic correspondence between stochastic differential equations and the Martin-Siggia-Rose formalism** <br>
  A.B., Claudio Dappiaggi, Nicolò Drago  <br>
  Annales Henri Poincaré  [DOI](https://doi.org/10.1007/s00023-025-01571-1)

* **An Algebraic and Microlocal Approach to the Stochastic Nonlinear Schrödinger Equation** <br>
  A.B., Claudio Dappiaggi, Paolo Rinaldi  <br>
  Annales Henri Poincaré 	24, 2443–2482 (2023) [DOI](https://doi.org/10.1007/s00023-023-01291-4)

  
## Preprints
* **Exotic B-series representation of the Feller semigroup for Itô diffusions and the MSR path integral** <br>
  A.B., arXiv preprint [DOI](https://arxiv.org/abs/2510.23102)

## Other writings
* **\"Holder-Besov spaces and space-time white noise** <br>
   with Fabrizio Zanella. Oberwolfach Reports. Arbeitsgemeinschaft: QFT and Stochastic PDEs (2023) [DOI](https://publications.mfo.de/handle/mfo/4106)
  
* **Algebraic methods for the perturbative analysis of stochastic equations** <br>
PhD Thesis [DOI](https://iris.unipv.it/bitstream/11571/1515063/2/thesis.pdf)

## Collaborators
* **[Claudio Dappiaggi](https://claudiodappiaggi.com/)**, University of Pavia <br>
* **[Nicolò Drago](https://nicolodrago.wixsite.com/mysite)**, University of Genova <br>
* **[Paolo Rinaldi](https://www.paolorinaldi.net/)**, University of Pavia <br>
* **[Lorenzo Zambotti](https://www.lpsm.paris/users/zambotti/index)**, Sorbonne Université, LPSM <br>
* **Beatrice Costeri**, University of Pavia <br>
* **[Francesco Caravenna](https://www.unimib.it/francesco-caravenna)**, University of Milano Bicocca <br>
* **Sonia Mazzucchi**, University of Trento <br>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
