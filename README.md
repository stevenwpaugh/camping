# camping

https://stevenwpaugh.github.io/camping/


List of all boxes:
{% assign bins = site.data.supplies | map: 'Bin' | join: ','  | split: ',' | uniq %}
{% for bin in bins %}
    {{ bin }}
{% endfor %}
