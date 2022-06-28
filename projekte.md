---
layout: page
title: projekte.
---

*Ich kann einen PC bedienen, seit meine Hand groß genug war eine Maus zu benutzen.* Das ist zumindest das, was ich Leuten sage, warum "ich so gut mit Computern kann". <br>
Die Wahrheit ist, dass ich gut mit Computern umgehen kann, weil ich es schon seit ewig und drei Tagen mache. Anfangs natürlich in einem sehr rudimentären Umfang auf dem alten Rechner von meinem Vater. Danach an den Rechnern, die wir in der Schule hatten. Dann an dem PC, den mir meine Eltern zum 16. Geburtstag geschenkt haben und ab dann an denen, die ich mir selber zusammengebaut habe. Es gab eine stetige Kurve an Eigenständigkeit und damit immer neue Probleme, die es zu lösen gab. 


<hr>

<div class="toc">
  <h2>inhalte.</h2>
  <ul class="texts">
  {% for item in site.texts %}
    {% and item.categories contains 'projekt' %}
    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>
