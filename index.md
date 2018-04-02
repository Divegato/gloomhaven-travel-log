---
title: Gloomhaven Travel Log
---
## Gloomhaven

### Travel Log
<table>
  <tr>
    <th>
      Sparkle Kids
    </th>
    <th>
      Sunstone Knights
    </th>
  </tr>
  {% for post in site.posts %}
    <tr>
      {% if post.team != 'Sparkle Kids' %}
      <td></td>
      {% endif %}
      <td>
        <h3>{{post.title}}</h3>
        {{post.excerpt}}
      </td>
      {% if post.team != 'Sunstone Knights' %}
      <td></td>
      {% endif %}
    </tr>
  {% endfor %}
</table>