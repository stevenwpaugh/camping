# camping

https://stevenwpaugh.github.io/camping/

{% assign boxes = site.supplies | map: 'Bin' | join: ',' | split: ',' | uniq %}

{% for box in boxes %}
    {{ box }}
{% endfor %}
