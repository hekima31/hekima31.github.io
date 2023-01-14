---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

I am a doctoral candidate focussing on the valorisation of liquid biofuels. The wetlab component of my work involves catalytic esterification of bio-oil compounds to enhance energy density and stability. The target use for our upgraded bio-oil is in the transport industry as a direct replacement of fossil fuel-derived petrol and diesel. Computationally, I used Density Function Theory to gain insights into the esterifcation mechanism , studying the energetics of intermediates, transition states, and the reactants and products to complement the data we get from the lab.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


