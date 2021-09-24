<p>
{{ site.data.ocr-gt.description }}
</p>

<ul> 
{% assign entries = site.data.ocr-gt | sort: 'id' %}
{% for item in entries %}
    <li>
        {{ item.name }}
    </li>
{% endfor %}
</ul> 
