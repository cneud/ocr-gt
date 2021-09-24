---
title: OCR and Ground Truth Resources
---

{{ site.data.ocr-gt.description }}


<ul> 
{% assign entries = site.data.ocr-gt | sort: 'id' %}
{% for item in entries %}
    <li>
        {{ item.name }}
    </li>
{% endfor %}
</ul> 
