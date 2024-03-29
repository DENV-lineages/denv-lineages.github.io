---
title: "Useful resources"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/dengue.jpeg
excerpt: "Lab protocols, bioinformatic pipelines, and helpful software"
---

{% for category in site.data.resource_categories %}
	
	<h3>{{category.name}}</h3>

	<section class="resourcesSection">
		{% for item in site.data.resources %}

			{% if item.category == category.name %}

				<div class="course">
					<div class="course-preview">
						<img src="assets/images/{{item.logourl}}"/>
					</div>
					<div class="course-info">
						
						<h6>{{item.subheading}}</h6>
						<h2>{{item.name}}</h2>
						<p>{{item.description}}</p><br><br>
						<a class="btn" href="{{item.link}}" style="color: white !important">View</a>
					</div>
				</div>
			{% endif %}
		{% endfor %}  
	</section>
	

{% endfor %}