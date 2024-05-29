---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

### Invited talks

| When | Where | Conference | Title |  
|:--------:|:-------|:-------|:--------|
|-----------------------------|
| May 2024  | Université De Lorraine |  ecorated Tree-like structures for singular dynamics | An interactive field approach to the stochastic sine-Gordon model}{Department of mathematics   |
| May 2024  | Université De bretagne Occidentale |  Rencontre ANR 2024 | An interactive field approach to the stochastic sine-Gordon model}{Department of mathematics   |
| April 2024  | University of Potsdam  | | Convergence results in the stochastic sine-Gordon model: An algebraic viewpoint   |
| December 2022  | University of Genova | | Stochastic nonlinear Schrödinger equation from an algebraic and microlocal viewpoint   |
| December 2022    | University of Trento |  | Stochastic nonlinear Schrödinger equation, an algebraic point of view   |
| October 2022   | University of Trento  | | Algebraic formulation of the SDE-Path integral correspondence   |

### Contributed talks

| When | Where |  Conference | Title |  
|:--------:|:-------| :-------|:--------|
|-----------------------------|
|December 2023  |  Mathematisches Forschungsinstitut Oberwolfach   | Arbeitsgemeinschaft: QFT and Stochastic PDE | H¨older-Besov spaces and space-time white noise  |
|September 2023  | University of Pavia  | End-of-year seminars | What if Quantum Field Theory meets complex systems?  |
| September 2022    | University of Pavia | End-of-year seminars | A complex world   |
| September 2022   | Ravello  | XLVII Summer school on mathematical physics - GNFM | A microlocal and algebraic approach to SPDEs   |




{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
