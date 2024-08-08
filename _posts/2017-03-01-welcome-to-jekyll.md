---
layout: default
title: "Home"
---

<!-- Banner image right below the header -->
<div class="banner">
  <img src="/images/NK_cells.jpg" alt="Banner Image">
</div>

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}

<style>
  .banner img {
    width: 100%; /* Make the banner image full width */
    height: auto; /* Maintain aspect ratio */
    margin-bottom: 20px; /* Optional: add space below the banner */
  }
</style>


