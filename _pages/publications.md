---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


### Work in progress

* **More Than Just Carbon: The Socioeconomic Impact of Large-Scale Tree Planting**, with Jeffrey Pagel
* **Oil Spills, Agricultural Production and Deforestation in Nigeria**, with Elena Perra and Marco Sanfilippo
* **Policy Layering and Biodiversity Additionality in Indonesia**, with Ben Groom and Charles Palmer
* **Carbon Pricing in Presence of Permeable Borders: The Case of British Columbia’s 2008 Carbon Tax**


