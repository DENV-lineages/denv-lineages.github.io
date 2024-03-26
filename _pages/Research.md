---
title: "Research"
layout: splash
permalink: /_pages/Research/
date: 2017-03-03T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
intro: 
  - excerpt: 'Overall, my research is about combining genomic and non-genomic data to learn about how viruses spread in space and time. I do this by using the field of phylodynamics, the combination of evolution, epidemiology and immunology.'
  
  
feature_row2:
 - title: "Spatial spread of viruses"
   excerpt: "I spend much of my time doing phylogeographic analyses on large and small datasets. These analyses use sample locations to infer how location has evolved along a phylogeny over time: in other words, where and when did the virus move in the past?
   This can be done in a discrete way, using eg countries as the location, and non-genomic data can be included to find out what predicts movement between locations. 
   Location can also change continuously, enabling a more accurate investigation of how a virus may spread within a country. Both can be used to identify source-sink dynamics and identify targetted non-pharmaceutical interventions."
   
feature_row3:
 - title: "Practical phylogenetics"
   excerpt: "Phylodynamics is great, but it's slow and can be complicated to interpret. Condensing genomic information into easier to understand analyses with quick turnaround times has been an important part of my career so far. 
   I was a co-developer on [civet](https://cov-lineages.org/resources/civet.html) and [grinch](https://cov-lineages.org/index.html#global_reports), both designed to make the huge amount of SARS-CoV-2 genomic data accessible and useable for data producers and the general public respectively.
   In my current job, I'm developing a tool to designate and assign lineages for Dengue virus (similar to the [pango lineage system](https://www.pango.network/)) to better describe global Dengue diversity, again without the need to perform complex analyses.
   "
   
feature_row4:
 - title: "Synthetic epidemics"
   excerpt: "Most of my PhD was spent developing a [simulator](https://github.com/ViralVerity/ABSynthE) to explore the spread of Ebola virus in Sierra Leone. Every person in Sierra Leone is assigned a contact network based on a hierarchical population structure.
   It then runs a stochastic Ebola epidemic through this contact network and spits out phylogenetic trees.
   The aim is at some point to use this to test assumptions about how which samples we sequence in epidemics to produce the most accurate results with the fewest resources used.
   This aim is currently unfinished (thanks COVID) but it has shown me where to push Python to its limits of memory usage and time efficiency, and also how to write recursive functions which won't crash my computer.
   " 
 

---


{% include feature_row id="intro" type="center" %}
{% include feature_row id="feature_row2" type="center" %}
{% include feature_row id="feature_row3" type="center" %}
{% include feature_row id="feature_row4" type="center" %}