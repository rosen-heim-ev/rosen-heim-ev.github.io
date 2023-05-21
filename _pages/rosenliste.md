---
title: Rosenliste
---
<style>
      tr:nth-of-type(odd) {
      background-color:#fae3f3;
    }
</style>

<table>
  {% for row in site.data.rosenliste %}
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
