---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


**Angelin-Bonnet, O.**, Biggs, P. J., Baldwin, S., Thomson, S., & Vignes, M. (2020). sismonr: simulation of *in silico* multi-omic networks with adjustable ploidy and post-transcriptional regulation in R. *Bioinformatics*,36(9), 2938-2940. [https://doi.org/10.1093/bioinformatics/btaa002](https://doi.org/10.1093/bioinformatics/btaa002)

* sismonr CRAN page: [https://CRAN.R-project.org/package=sismonr](https://CRAN.R-project.org/package=sismonr)
* sismonr tutorial (GitHub page): [https://oliviaab.github.io/sismonr/](https://oliviaab.github.io/sismonr/)

 &nbsp;  

**Angelin-Bonnet, O.**, Biggs, P. J., & Vignes, M. (2019). Gene regulatory networks: a primer in biological processes and statistical modelling. In *Gene Regulatory Networks* (pp. 347-383). Humana Press, New York, NY. [https://link.springer.com/protocol/10.1007/978-1-4939-8882-2_15](https://link.springer.com/protocol/10.1007/978-1-4939-8882-2_15)

* Preprint available at [https://arxiv.org/abs/1805.01098](https://arxiv.org/abs/1805.01098)

&nbsp;   

**Angelin-Bonnet, O.**, Biggs, P. J., & Vignes, M. (2018). The sismonr Package: Simulation of In Silico Multi-Omic Networks in R. In *2018 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)* (pp. 2729-2731). IEEE. [https://doi.org/10.1109/BIBM.2018.8621131](https://doi.org/10.1109/BIBM.2018.8621131)

{% comment %}
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}
