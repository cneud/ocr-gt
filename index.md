---
title: "ocr-gt"
---

<ul> 
{% assign entries = site.data.ocr-gt.entries | sort: 'id' %}
{% for item in entries %}
    <li>
        <strong>{{ item.name }}</strong>. {{ item.description }}
    </li>
{% endfor %}
</ul> 
