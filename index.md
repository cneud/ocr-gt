---
title: "ocr-gt"
---

<ul> 
{% assign entries = site.data.ocr-gt.entries | sort: 'id' %}
{% for item in entries %}
    <li>
        {{ item.name }}
        {{ item.description }}
    </li>
{% endfor %}
</ul> 
