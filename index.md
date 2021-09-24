---
title: "ocr-gt"
---

<ul> 
{% assign entries = site.data.ocr-gt.entries | sort: 'id' %}
{% for item in entries %}
    <li>
        <strong>{{ item.name }}</strong><br> 
        {{ item.description }}<br>
        <a href="{{ item.url }}"></a>
    </li>
{% endfor %}
</ul> 
