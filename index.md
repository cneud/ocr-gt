---
title: "OCR and Ground Truth Resources"
---

<div>
{{ site.data.ocr-gt.description }}

<ul> 
<!-- {% assign entries = site.data.ocr-gt | sort: 'id' %} -->
{% for item in site.data.ocr-gt %}
    <li>
        {{ item.name }}
    </li>
{% endfor %}
</ul> 
</div>