---
title: Rosenliste
---

<table>
  {% assign roses = site.data.rosenliste | sort_natural %}
  {% for row in roses %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th style="font-weight: 900">{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}

    {% tablerow pair in row %}
      {{ pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>
