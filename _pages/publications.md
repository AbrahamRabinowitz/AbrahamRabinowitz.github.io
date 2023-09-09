---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## [Szegő kernel asymptotics and concentration of Husimi Distributions of eigenfunctions](https://arxiv.org/abs/2202.14013)

### In this paper we derive scaling asymptotics for tempered sums of Husimi Distributions within a parabolically frequency rescaled neighborhood of a neighborhood of the flow of the classical dynamics. The asymptotic formulae are expressed in terms of the metaplectic representation of the linearization of the geodesic flow on Bargmann-Fock Space. As a corollary we obtain sharp $L^p$ estimates for Husimi Distributions on the Grauert Tube Boundary.

(Joint with Robert Chang) *Szegő kernel asymptotics and concentration of Husimi Distributions of eigenfunctions (preprint submitted to Communications in Analysis and Geometry)*

## [Scaling asymptotics for Szegő kernels on Grauert tubes](https://arxiv.org/abs/2107.05105)

### In this paper we explain an extension of a theory of phase space quantum mechanics to curved surfaces and provide scaling asymptotics of tempered sums of complexified Laplace eigenfunctions in a parabolically frequency rescaled neighborhood of the diagonal. We recover the Szego kernel for reduced Heisenberg space as the leading order term, providing evidence for the Grauert Tube setting as an appropriate generalization of Husimi Distributions on Bargmann-Fock space.

(Joint with Robert Chang)*Scaling Asymptotics for Szegő Kernels on Grauert Tubes (Published in the [Journal of Geometric Analysis](https://link.springer.com/article/10.1007/s12220-022-01116-6))*

For an explanation of this research tailored to a more general audience (with some necessary corners cut), please see [here](https://abrahamrabinowitz.github.io/files/GeneralAudienceSlides.pdf).


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
