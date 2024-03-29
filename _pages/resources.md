---
title: "Useful resources"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/dengue.jpeg
excerpt: "Lab protocols, bioinformatic pipelines, and helpful software"
---

<div class="splash_section" id="software_logos">
		{% for item in site.data.resources %}
            {{item.category}}
			{% if item.category == category.name %}
				<figure class="effect-duke">
					<img src="assets/images/{{item.picture}}"/>
					<figcaption>
						<p>
							{{item.name}}<br>
							<span class="duke-description">{{item.description}}</span>
						</p>
						<a class="btn" href="{{item.link}}" style="color: white !important">View</a>
					</figcaption>			
				</figure>

			{% endif %}
				
		{% endfor %}
</div>