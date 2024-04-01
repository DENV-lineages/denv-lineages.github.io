---
title: "Dengue lineage designation rules"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/dengue.jpeg
  actions:
    - label: "Submit lineage designations here"
      url: "https://github.com/DENV-lineages/denv-lineage-designation/issues"
figure1:
  - image_path: "/assets/images/genome_detective.svg"
    alt: "figure one"
    title: "Figure one"
---

This page contains instructions on **designating new lineages**. In other words, these are the rules for suggesting a new sub-genotypic grouping. If you are looking for where to assign an existing lineage to new sequences, please use one of our partner assignment tools, found on the [resources page](/_pages/resources/).

- For the rules and thresholds that a new lineage must satisfy to go [rules](#rules). 
- For how to name a new lineage go to [names](#names). 
- For the practicalities of how you actually submit a naming request go to [how to submit a designation request](#how-to-submit-a-designation-request)
- For information on how often we review requests go to [review timelines](#review-timelines)
- For other issues, try our [frequently asked questions](/_pages/faq/) 

## Rules

There are three rules which must be met for a putative new lineage to be named. 

We note that we designate lineages based on defining **nodes** - i.e. all of the tips downstream of this node will be included in the lineage definition.

1. The branch leading up to the defining node should be **at least 25 substitutions long**
2. There should be at least **15 sequences** in the putative clade
3. There should be at least one **sister lineage** the same number of nodes away from the parent defining node. This may be an existing or a new lineage. 

We understand that third rule in particular may be challenging to do manually, and so we provide some python scripts for identifying sister lineages [here](https://github.com/DENV-lineages/lineages-paper). We do not recommend using the scripts on this repository for branch length because they are specific to our alignment length.

Figure one shows examples of acceptable and non-acceptable lineage suggestions:

{% include gallery id="figure1" caption="Figure one: examples of putative lineages and how they fit with the rules" %}





## Names

## How to submit a designation request

## Review timelines