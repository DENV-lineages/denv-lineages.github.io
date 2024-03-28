---
title: "Dengue lineages"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/dengue.jpeg
excerpt: "This is a website for all things dengue lineages. It is currently under construction - watch this space!"
intro: 
  - excerpt: 'If you used information on this website, please cite [this paper]()'
feature_row_gd:
  - image_path: "/assets/images/genome_detective.png"
    alt: "Genome detective logo"
    title: "Genome Detective Typing Tool"
    url: "https://www.genomedetective.com/app/typingtool/dengue/"
    btn_label: "Go to website"
    btn_class: "btn--inverse"
feature_row_glue:
  - image_path: "/assets/images/glue.png"
    alt: "GLUE logo"
    title: "GLUE (NB tool not ready yet, this is a placeholder)"
    url: "http://glue-tools.cvr.gla.ac.uk/#/home"
    btn_label: "Go to website"
    btn_class: "btn--inverse"

---

{% include feature_row id="intro" type="center" %}
Looking to assign sequences to a lineage? Use one of these tools:
{% include feature_row id="feature_row_gd" type="left" %}
{% include feature_row id="feature_row_glue" type="right" %}
