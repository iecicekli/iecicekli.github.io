---
layout: archive
title: "Writing"
permalink: /writing/
author_profile: true
---

{% if author.arxiv %}
  You can also find my articles on <u><a href="{{author.arxiv}}">my arXiv page</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Texts
- [Graduation Project on Hyperbolic Geometry (Spring '23)](../files/graduation_project.pdf)
- [Kuadratik karşılıklılığın bir ispatı (with Ayberk Zeytin) (Spring '23)](../Gauss-Sums.pdf)

## Notes and Presentations

- [Linear Algebra ('21)](../files/Linear Algebra.pdf).
- [Algebraic deRham Theory (with Mert Akdenizli) (Spring '23)](../files/AlgDeRham.pdf).
- [Discrete Morse Theory (with Eliz Gündüz) (Spring '23)](../files/TDA_morse.pdf).