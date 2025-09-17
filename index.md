---
layout: page
title:
permalink: /
people:
pubs:
  - title: "A level-set based finite difference method for the ground state Bose-Einstein condensates in smooth bounded domains"
    author: "H. Lee, Y. Liu"
    journal: "Preprint"
    arxiv: "https://arxiv.org/abs/2509.00668"
    year: "2025"

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

I am an Assistant Professor in the [Department of Mathematics]
at the [New York Institute of Technology].

Previously, I was a Visiting Assistant Professor at the [Georgia Institute of Technology].

I received my PhD in Applied Mathematics from [Columbia University]
under the supervision of [Qiang Du].

[[hlee50@nyit.edu]] [[CV]: updated 2025/09].

### Research Interests

My research interests lie in the numerical analysis of nonlocal models, hyperbolic conservation laws, machine learning methods, and optimal transport theory.

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

#### **New York Tech**

- Fall 2025: MATH 170 (Calculus I), MATH 310 (Linear Algebra)
- Spring 2025: MATH 260 (Calculus II)
- Fall 2024: MATH 320 (Differential Equations), MATH 260 (Calculus III)

#### **Georgia Tech** _(Instructor)_

- Fall 2021 – Spring 2024 (every semester): MATH 1552 (Integral Calculus)

#### **Columbia University** _(Teaching Assistant)_

- Fall 2019 – Spring 2020: APMA E2000 (Multivariable Calculus)

<a rel="me" href="https://fosstodon.org/@dsrim"></a>

[Qiang Du]: https://www.apam.columbia.edu/faculty/qiang-du
[CV]: files/Donsub_Rim_CV.pdf
[hlee50@nyit.edu]: mailto:hlee50@nyit.edu
[github page]: https://github.com/dsrim/
[Columbia University]: https://apam.columbia.edu
[Department of Mathematics]: https://www.nyit.edu/academics/arts-and-sciences/mathematics/
[New York Institute of Technology]: https://nyit.edu
[Georgia Institute of Technology]: https://www.gatech.edu/
