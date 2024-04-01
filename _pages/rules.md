---
title: "Dengue lineage designation rules"
layout: dengue_layout
classes: wide
toc: false
toc_sticky: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/dengue.jpeg
  actions:
    - label: "Submit lineage designations here"
      url: "https://github.com/DENV-lineages/denv-lineage-designation/issues"
figure1:
  - image_path: "/assets/images/designation_rules.svg"
    alt: "figure one"
    title: "Figure one"
---

This page contains instructions on **designating new lineages**. In other words, these are the rules for suggesting a new sub-genotypic grouping. If you are looking for where to assign an existing lineage to new sequences, please use one of our partner assignment tools, found on the [resources page](/_pages/resources/).

- For an overview of the system, go to [overview](#overview)
- For the rules and thresholds that a new lineage must satisfy to go [rules](#rules). 
- For how to name a new lineage go to [names](#names). 
- For the practicalities of how you actually submit a naming request go to [how to submit a designation request](#how-to-submit-a-designation-request)
- For information on how often we review requests go to [review timelines](#review-timelines)
- For other issues, try our [frequently asked questions](/_pages/faq/) 

## Overview

This system is built off experience developing lineage systems for other viruses of public health importance, and is the result of a global collaboration of researchers and public health professionals. It aims to provide additional spatial and temporal resolution with which to discuss the large genetic diversity of dengue virus. Specifically, it splits up existing genotypes into smaller groups and provides a standardized, neutral naming system.

Broadly speaking, we define **major** and **minor** lineages within each genotype. These lineages are defined by the same [rules](#rules), but use different [nomenclature](#names). In theory, minor lineages should be more useful for country-specific questions, and major lineages for regional questions. Of course, it won't always necessarily work that - some minor lineages are very widepsread, and some major lineages are geographically limited. 

We designated an initial set of lineages based on all publicly available whole genome sequences with coverage greater than 70% in mid-2023. We envision two ways of generating new lineage suggestions. The first is through [community effort via a github repo](#how-to-submit-a-designation-request), which is what this page is designed to help with. Here, members of the dengue research/public health community can suggest new lineages to help with their surveillance efforts. These will be reviewed with some [regularity](#review-timelines) and given a "putative" name. The second method is an annual review, where all publicly available whole genome data is run through custom scripts to ensure that all new lineages have been identified, including appropriate putative ones suggested throughout the year. These will then be reviewed by an advisory board and assignment tools are updated. 

The community effort therefore is a way of getting a lineage designation **in between** annual reviews, although if it is a valid lineage, rest assured that it will be included in the system at the annual review regardless of whether it is pitched on the github repository.

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

The nomenclature system is split into two 

## How to submit a designation request

## Review timelines