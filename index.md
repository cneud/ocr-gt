---
title: "ocr-gt"
---

For additional details or contributions, please visit [https://github.com/cneud/ocr-gt](https://github.com/cneud/ocr-gt).

<ul>
{% assign entries = site.data.ocr-gt.entries | sort: 'id' %}
{% for item in entries %}
    <li>
        <strong>{{ item.name }}</strong><br>
        {{ item.description }}<br>
        <a href="{{ item.url }}">{{ item.url }}</a>
    </li>
{% endfor %}
</ul>
