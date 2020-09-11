---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% comment %}
* **UCLA - Research Frontiers in Biomathematics Seminar** (expected November 2020)
  * Gene Regulatory Networks Simulation (speaker)

&nbsp;   
 {% endcomment %}

* **NeSI webinar series** - online - (expected October 2020)
  * Simulating Gene Regulatory Networks on HPC (speaker)

&nbsp;  

* **Thematic Month on Mathematical Issues in Biology – CIRM** - Marseille, France - February-March 2020
  * Simulating post-transcriptional regulation, ploidy and more with the sismonr package (poster)

&nbsp;  


* **New Zealand Statistical Association (NZSA) 2019** - Dunedin, New Zealand - 
  * Causal Inference of Gene Regulatory Networks (oral presentation)
  * Honourable Mention Student Talk Award

&nbsp;  

* **DECO2019 - The Interface of Mathematics and Biology** - Napier, New Zealand - February 2019
  * Simulating gene expression profiles with the R package sismonr (oral presentation)

&nbsp;  

* **IEEE International Conference on Bioinformatics and Biomedicine (BIBM) 2019** - Madrid, Spain - December 2018
 * The sismonr package: Simulation of In Silico Multi-Omic Networks in R (poster)
 * Grant: Massey University Postgraduate Travel Gran
 * Program Committee member of the associated *Workshop on challenges and opportunities in Large Scale Network Analysis in Systems Biology*

&nbsp;  

* **New Zealand Statistical Association (NZSA) 2018** - Palmerston North, New Zealand - November 2018
  * How R and Julia hang out together to simulate complex (oral presentation)
  * Won the Best Student Talk Award

&nbsp;  

* **New Zealand Mathematics and Statistics Postgraduate Conference (NZMASP) 2018** - Waikanae, New Zealand - November 2018
  * How R and Julia hang out together to simulate complex (oral presentation)
  * Member of the Organising Committee

{% comment %}
{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
{% endcomment %}
