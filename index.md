---
layout: page
title:
permalink: /
people:
pubs:
  - title: "A PNP ion channel deep learning solver with local neural network and finite element input data"
    author: "H. Lee, Z. Chao, H. Cobb, Y. Liu, D. Xie"
    journal: "Machine Learning: Science and Technology"
    doi: "https://doi.org/10.1088/2632-2153/ad7e7a"
    arxiv: "https://arxiv.org/abs/2401.17513"
    numbers: "**5** 045001"
    year: "2024"

  - title: "A ghost-point based second order accurate finite difference method on uniform orthogonal grids for electromagnetic scattering around curved perfect electric conductors with corners"
    author: "H. Lee, Y. Liu"
    journal: "Journal of Computational Physics"
    doi: "https://doi.org/10.1016/j.jcp.2023.112314"
    numbers: "**490** 112314"
    year: "2023"

  - title: "Solving Maxwell's Equation in 2D with Neural Networks with Local Converging Inputs"
    author: "H. Cobb, H. Lee, Y. Liu"
    journal: "Preprint"
    arxiv: "https://arxiv.org/abs/2302.02860"
    year: "2023"

  - title: "Second-order accurate Dirichlet boundary conditions for linear nonlocal diffusion problems"
    author: "H. Lee, Q. Du"
    journal: "Communications in Mathematical Sciences"
    arxiv: "https://arxiv.org/abs/2108.11817"
    doi: "https://dx.doi.org/10.4310/CMS.2022.v20.n7.a2"
    numbers: "**20** (7) 1815-1837"
    year: "2022"

  - title: "Nonlocal gradient operators with a nonspherical interaction neighborhood and their applications"
    author: "H. Lee, Q. Du"
    journal: "ESAIM: Mathematical Modelling and Numerical Analysis"
    doi: "https://doi.org/10.1051/m2an/2019053"
    numbers: "**54** (1) 105-128"
    year: "2020"

  - title: "Asymptotically compatible SPH-like particle discretizations of one dimensional linear advection models"
    author: "H. Lee, Q. Du"
    journal: "SIAM Journal on Numerical Analysis"
    doi: "https://doi.org/10.1137/18M1175215"
    numbers: "**57** (1) 127-147"
    year: "2019"
---

{% include image.html url="images/Hwi_Lee_Profile.jpg" caption="" width="300px" align="right" %}

### About

I am an Assistant Professor at the [Department of Mathematics]
in [New York Institute of Technology].

I was a visiting assistant professor at the [Georgia Institute of Technology].

I obtained my PhD at the [Columbia University] and my
advisor was [Qiang Du].

[[hlee50@nyit.edu]] [[CV]: updated 2025/07/01].

### Research Interests

My interests are in the numerical analysis of nonlocal models, hyperbolic conservation laws, machine learning and optimal transport.

### Publications / Preprints

{% for pub in page.pubs %}
{% if pub.image %}{% include image.html url=pub.image caption="" height="100px" align=thumbnail %}{% endif %}
{% if pub.url %}[**{{pub.title}}**]({{pub.url}}){% else %}
{% if pub.doi %}[**{{pub.title}}**]({{pub.doi}}){% else %}
{% if pub.arxiv %}[**{{pub.title}}**]({{pub.arxiv}}){% else %}
{% if pub.earxiv %}[**{{pub.title}}**]({{pub.earxiv}}){% else %}
{% if pub.preprint %}[**{{pub.title}}**]({{pub.preprint}}){% else %}
**{{pub.title}}**{% else %}{% endif %}{% endif %}{% endif %}{% endif %}{% endif %}<br />
{{pub.author}}<br />
_{{pub.journal}}_ {% if pub.note %} _({{pub.note}})_{% endif %}{% if pub.numbers %}{{pub.numbers}}{% endif %} ({{pub.year}}) | {% if pub.doi %}[[doi]({{pub.doi}})]{% endif %}{% if pub.arxiv %}[[arXiv]({{pub.arxiv}})]{% endif %}{% if pub.earxiv %}[[EarthArXiv]({{pub.earxiv}})]{% endif %}{% if pub.preprint %}[[Preprint]({{pub.preprint}})]{% endif %}{% if pub.github %}[[github]({{pub.github}})]{% endif %}{% if pub.media %}<br />Media: {% for article in pub.media %}[[{{article.name}}]({{article.url}})]{% endfor %}{% endif %}{% endfor %}

### Teaching

At New York Tech

- Spring 2025: MATH 260 (Calculus II)
- Fall 2024: MATH 320 (Differential Equations), MATH 260 (Calculus III)

At Georgia Tech

- Spring 2024: MATH 1552 (Integral Calculus) - Instructor (two sections)
- Fall 2023: MATH 1552 (Integral Calculus) - Instructor
- Spring 2023: MATH 1552 (Integral Calculus) - Instructor (two sections)
- Fall 2022: MATH 1552 (Integral Calculus) - Instructor
- Spring 2022: MATH 1552 (Integral Calculus) - Instructor
- Fall 2021: MATH 1552 (Integral Calculus) - Instructor

At Columbia University

- Spring 2020: APMA E2000 (Multivariable Calculus) - Teaching Assistant
- Fall 2019: APMA E2000 (Multivariable Calculus) - Teaching Assistant

<a rel="me" href="https://fosstodon.org/@dsrim"></a>

[Qiang Du]: https://www.apam.columbia.edu/faculty/qiang-du
[CV]: files/Donsub_Rim_CV.pdf
[hlee50@nyit.edu]: mailto:hlee50@nyit.edu
[github page]: https://github.com/dsrim/
[Columbia University]: https://apam.columbia.edu
[Department of Mathematics]: https://www.nyit.edu/academics/arts-and-sciences/mathematics/
[New York Institute of Technology]: https://nyit.edu
[Georgia Institute of Technology]: https://www.gatech.edu/
