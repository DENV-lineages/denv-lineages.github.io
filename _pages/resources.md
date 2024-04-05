---
title: "Useful resources"
layout: dengue_layout
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/dengue.jpeg
excerpt: "Lab protocols, bioinformatic pipelines, and helpful software"
toc: true
toc_sticky: true
classes: wide

---

<div>
    {% for category in site.data.resource_categories %}
        <header><h2> {{category.name}} </h2></header>
        <div>
                {% for item in site.data.resources %}
                    {% if item.category == category.name %}
                    <header><h3> [{{item.name}}]({{item.link}}) </h3></header>
                    <p>{{item.description}} </p>
                        <!-- <figure class="effect-duke">
                            <img src="/assets/images/{{item.picture}}"/>
                            <figcaption>
                                <p>
                                    {{item.name}}<br>
                                    <span class="duke-description">{{item.description}}</span>
                                </p>
                                <a class="btn" href="{{item.link}}" style="color: white !important">Go to website</a>
                            </figcaption>			
                        </figure> -->

                    {% endif %}	
                {% endfor %}
        </div>
    {% endfor %}
</div> 