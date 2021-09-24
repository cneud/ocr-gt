---
layout: page
title: OCR and Ground Truth Resources
---

{{ site.data.ocr-gt.description }}

<!--  Loop through the entries in site.data.ocr-gt and display them in a nice way here  -->
<ul> 
{% assign entries = site.data.ocr-gt | sort: 'id' %}
{% for item in entries %}
    <li>
        {{ item.name }}
    </li>
{% endfor %}
</ul> 
