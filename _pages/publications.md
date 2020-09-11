---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Test new publication:

**Angelin-Bonnet, O.**, Biggs, P. J., Baldwin, S., Thomson, S., & Vignes, M. (2020). sismonr: simulation ofin silicomulti-omic networks with adjustable ploidy and post-transcriptional regulation in R. *Bioinformatics*,36(9), 2938-2940. [https://doi.org/10.1093/bioinformatics/btaa002](https://doi.org/10.1093/bioinformatics/btaa002)

sismonr CRAN page: [https://CRAN.R-project.org/package=sismonr](https://CRAN.R-project.org/package=sismonr)

sismonr tutorial (GitHub page): [https://oliviaab.github.io/sismonr/](https://oliviaab.github.io/sismonr/)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
