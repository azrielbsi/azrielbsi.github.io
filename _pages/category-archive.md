---
title: School Programs
layout: categories
permalink: /categories/
author_profile: false
header:
  overlay_image: /assets/images/header/apple-eye.jpg
  overlay_filter: 0.5
sidebar:
  - title: "Category"
    image: "/assets/images/sidebar/category.png"
    image_alt: "category"
    text: "Informasi tambahan untuk memahami dengan lebih baik apa yang Anda cari dalam kategori atau topik tertentu."
---

{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "posts" %}
    {% capture label %}{{ collection.label }}{% endcapture %}
    {% if label != written_label %}
      <h2 id="{{ label | slugify }}" class="archive__subtitle">{{ label }}</h2>
      {% capture written_label %}{{ label }}{% endcapture %}
    {% endif %}
  {% endunless %}
  {% for post in collection.docs %}
    {% unless collection.output == false or collection.label == "posts" %}
      {% include archive-single.html %}
    {% endunless %}
  {% endfor %}
{% endfor %}
