---
layout: page
title: projects
permalink: /projects/
description: Research and policy projects
nav: true
nav_order: 3
display_categories: [dissertation, lab research, policy research]
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>

---

<div class="small" markdown="1">

**Image credits**

- A cracked solar panel near Leh, India. Photo: Kiran Jonnalagadda, <a href="https://commons.wikimedia.org/wiki/File:Cracked_solar_panel_near_Leh_(4336613925).jpg">Wikimedia Commons</a>, <a href="https://creativecommons.org/licenses/by-sa/2.0/">CC BY-SA 2.0</a>.
- Solar panels at Wold Farm, East Riding of Yorkshire. Photo: David Brown, <a href="https://commons.wikimedia.org/wiki/File:Solar_panels_at_Wold_Farm_(geograph_6386472).jpg">Wikimedia Commons</a>, <a href="https://creativecommons.org/licenses/by-sa/2.0/">CC BY-SA 2.0</a>.
- First Solar's Desert Sunlight solar farm, which uses CdTe modules. Photo: U.S. Department of the Interior, <a href="https://commons.wikimedia.org/wiki/File:02-09-15_First_Solar_Desert_Sunlight_Solar_Farm_(15863210084).jpg">Wikimedia Commons</a>, <a href="https://creativecommons.org/licenses/by-sa/2.0/">CC BY-SA 2.0</a>.
- An anodized aluminum frame being attached to a PV module. Photo: Nosferatu it, <a href="https://commons.wikimedia.org/wiki/File:Pv_module_lamination_05.jpg">Wikimedia Commons</a>, <a href="https://creativecommons.org/licenses/by-sa/3.0/">CC BY-SA 3.0</a>.
- A reusable coffee cup. Photo: Keepcupwiki, <a href="https://commons.wikimedia.org/wiki/File:KeepCup_Brew_Cork_Reusable_Coffee_Cup.jpg">Wikimedia Commons</a>, <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a>.
- Electricity meters in India. Photo: Balaji Kasirajan, <a href="https://commons.wikimedia.org/wiki/File:Electricity_meters_in_India.JPG">Wikimedia Commons</a>, <a href="https://creativecommons.org/licenses/by-sa/3.0/">CC BY-SA 3.0</a>.
- Station Road in Tanakpur, India. Photo: ArmouredCyborg, <a href="https://commons.wikimedia.org/wiki/File:Station_Road,_Tanakpur.jpg">Wikimedia Commons</a>, <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a>.
- Map of South Asia. Map: DrQuantum, <a href="https://commons.wikimedia.org/wiki/File:South_Asia_(orthographic_projection)_with_national_boundaries.png">Wikimedia Commons</a>, <a href="https://creativecommons.org/licenses/by-sa/3.0/">CC BY-SA 3.0</a>.

</div>
