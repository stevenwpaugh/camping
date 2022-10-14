# camping

https://stevenwpaugh.github.io/camping/

{% assign boxes = site.supplies | map: 'Bin' | join: ',' | split: ',' | uniq %}
List of Boxes:
{% for box in boxes %}
    {{ box }}
{% endfor %}
