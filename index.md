---
title: "ocr-gt"
---

<ul> 
{% assign entries = site.data.ocr-gt.entries | sort: 'id' %}
{% for item in entries %}
    <li>
        <strong>{{ item.name }} [{{ item.id }}]</strong><br> 
        {{ item.description }}<br>
        {{ item.url }}
    </li>
{% endfor %}
</ul> 
