---
title: Wild- und Heilpflanzen
---
<style>
      tr:nth-of-type(odd) {
      background-color:#e0ffe2;
    }
</style>

<table>
  {% for row in site.data.begleitpflanzen %}
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
