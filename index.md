---
title: "OCR and Ground Truth Resources"
---

<p>{{ site.data.ocr-gt.description }}</p>

<ul> 
{% assign entries = site.data.ocr-gt.entries | sort: 'id' %}
{% for item in entries %}
    <li>
        {{ item.name }}
        {{ item.description }}
    </li>
{% endfor %}
</ul> 
