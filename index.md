---
title: "OCR and Ground Truth Resources"
---

<!-- {{ site.data.ocr-gt.description }} -->

<ul> 
<!-- {% assign entries = site.data.ocr-gt.entries | sort: 'id' %} -->
{% for item in site.data.ocr-gt.entries %}
    <li>
        {{ item.name }}
    </li>
{% endfor %}
</ul> 
