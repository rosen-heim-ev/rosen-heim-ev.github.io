---
title: 'Rosengarten'
subtitle: 'Bepflanzungskonzept und Rosen'
date: 2023-05-01 00:00:00
description: 
featured_image: '/images/projects/rosengarten.jpg'
---

<style>
      tr:nth-of-type(odd) {
      background-color:#fae3f3;
    }
</style>

<div class="wrap" style='background-color:#C182AE; color: #000000; border-left: solid #9F1F79 4px; padding:0.7em;'>
<span>
<img src="/images/info-icon.png" height="30pt" width="30pt"> 
<p style='margin-top:1em; text-align:center'>
<b>Natur gärtnert mit</b></p>
<p style='margin-left:1em;  margin-bottom:1em; text-align:justify; max-width: fit-content'>
Die Bepflanzungslisten sind nur zur Orientierung gedacht. Es kann durchaus sein, dass einzelne Pflanzen in den Listen nicht mehr im Garten zu finden sind.
<br>
Für aktuelle Informationen, nehmen sie gerne mit uns Kontakt auf!
</p>
</span>
</div>

In diesem Projekt versuchen wir wilde, historische, und alte Rosen zusammenzutragen. Der zeitliche Rahmen erstreckt sich von der Antike bis 1867.
Die Sammlung ist noch nicht komplett.

Damit die Beete schnell früh blühen, gut zu pflegen und auch für die Tierwelt interessant sind, haben wir in alle Beeten Wildpflanzen gepflanzt, die mit ihrer Fülle und Farbe die Beete zu allen Jahreszeiten bereichern.


## Lageplan

Die Gartenanlage ist unterteilt in Beete (B1 - B4), und Aussenbereiche (A1 - A10). Die Beete sind nach verschiedenen Zeiten und Orten organisiert.

![](/images/rosengarten_bereiche_plan.png)

## Blühkalender

Die beste Zeit um den Rosengarten zu besuchen ist der Juni. Zu diesem Zeitpunkt blühen die meisten der gepflanzten Rosen. Dennoch sind auch zu anderen Jahreszeiten verschiedene blühende Pflanzen anzutreffen.

<div class="wrap"> 
    <img src="/images/projects/bluehkalender.png" style="margin-left: auto; margin-right: auto">
</div>


## Beet 1: Karl der Grosse (Capitulare De Villis)
Das Beet 1 (B1) ist der Zeit um Karl den Großen gewidmet und der Landgüterverordnung, dem Capitulare de villis. Diese Verordnung wurde ungefähr um 800 n. Chr. zur Verwaltung der Krongüter erlassen und enthielt eine detaillierte Aufstellung von Pflanzen, die in den Gärten zur optimalen Versorgung angepflanzt werden sollten.
Ganz vorne werden Rose und Lilie genannt.

### Rosenliste
<table>
  {% for row in site.data.rosenliste %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th style="font-weight: 900">{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}
    {% if row["Standort"] contains "B1" %}
        {% tablerow pair in row %}
          {{ pair[1] }}
        {% endtablerow %}
    {% endif %}
  {% endfor %}
</table>

### Eindrücke
<div class="gallery" data-columns="3">
	<img src="/images/projects/flowerbeds/b1_apothekerrose.jpg">
	<img src="/images/projects/flowerbeds/b1_semiplena.jpg">
	<img src="/images/projects/flowerbeds/b1_quatre_saison.jpg">
	<img src="/images/projects/flowerbeds/b1_tapetenrose.jpg">
	<img src="/images/projects/flowerbeds/b1_the_bishop.jpg">
</div>


## Beet 2: Hildegard von Bingen
Das Beet 2 (B2) umfasst zusätzlich Pflanzen, die etwa zur Zeit der Hildegard von Bingen etwa ab 1100 in den Kloster- und Burggärten kultiviert wurden. Auch hier handelt es sich noch immer hauptsächlich um Heil- und Nutzpflanzen.
In diesem Beet finden sie auch die wichtigsten Marienpflanzen, die auf vielen mittelalterlichen Gemälden als Bestandteil des Mariengartens zu erkennen sind.

In den folgenden Jahrhunderten entstand ein stärkeres Naturinteresse. Es gab immer mehr botanische Beschreibungen. Sogenannte Pflanzenjäger brachten neue Pflanzenarten. Der Garten verlor den reinen Nutzcharakter und entwickelte sich zum Ziergarten. Es entstanden botanische Gärten (1525 Erfurt, 1530 Marburg) und reiche Bürger leisteten sich einen Garten.
Ein sehr gut dokumentierter Garten ist der Garten von Eichstätt, siehe Beet 3.

### Rosenliste
<table>
  {% for row in site.data.rosenliste %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th style="font-weight: 900">{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}
    {% if row["Standort"] contains "B2" %}
        {% tablerow pair in row %}
          {{ pair[1] }}
        {% endtablerow %}
    {% endif %}
  {% endfor %}
</table>


### Eindrücke
<div class="gallery" data-columns="3">
	<img src="/images/projects/flowerbeds/b2_duchess_de_portland.jpg">
	<img src="/images/projects/flowerbeds/b2_shailors_white_moss.jpg">
	<img src="/images/projects/flowerbeds/b2_hibernica.jpg">
	<img src="/images/projects/flowerbeds/b2_maidens_blush.jpg">
</div>


## Beet 3: Der Garten von Eichstätt (Hortus Eystettensis)
Im Beet 3 (B3) finden sich Pflanzen, die in dem Garten des Fürstbischofs von Gemmingen in Eichstätt angepflanzt waren. Die Liste wurde von dem Apotheker Basilius Besler 1613 in einem dicken Buch veröffentlicht.
Hier tauchen schon viele exotische Pflanzen auf.
Sie finden hier Pflanzen, die im 17. Jahrhundert dazukamen und in den Gärten kultiviert wurden.


### Rosenliste
<table>
  {% for row in site.data.rosenliste %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th style="font-weight: 900">{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}
    {% if row["Standort"] contains "B3" %}
        {% tablerow pair in row %}
          {{ pair[1] }}
        {% endtablerow %}
    {% endif %}
  {% endfor %}
</table>

### Eindrücke
<div class="gallery" data-columns="3">
	<img src="/images/projects/flowerbeds/b3_centifolia_major.jpg">
	<img src="/images/projects/flowerbeds/b3_charles_de_mills.jpg">
	<img src="/images/projects/flowerbeds/b3_parvifolia.jpg">
	<img src="/images/projects/flowerbeds/b3_rose_de_peintres.jpg">
	<img src="/images/projects/flowerbeds/b3_york_andlancaster.jpg">
</div>

## Beet 4: Gartenpflanzen des 18. Jahrhunderts
Im Beet 4 (B4) sind alte Gartenpflanzen zu finden, die im 18. Jahrhundert dazu gekommen sind, damit Rosen und Begleitpflanzen den gleichen Zeitrahmen abdecken.

### Rosenliste
<table>
  {% for row in site.data.rosenliste %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th style="font-weight: 900">{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}
    {% if row["Standort"] contains "B4" %}
        {% tablerow pair in row %}
          {{ pair[1] }}
        {% endtablerow %}
    {% endif %}
  {% endfor %}
</table>

### Eindrücke
<div class="gallery" data-columns="3">
	<img src="/images/projects/flowerbeds/b4_fuchsrose.jpg">
	<img src="/images/projects/flowerbeds/b4_old_blush.jpg">
	<img src="/images/projects/flowerbeds/b4_rosa_mundi.jpg">
</div>

## Aussenbereich
Im Außenbereich sind Rosen gepflanzt worden, die sich zeitlich ab 1800 anschließen.

### Rosenliste
<table>
  {% for row in site.data.rosenliste %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th style="font-weight: 900">{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}
    {% if row["Standort"] contains "A" %}
        {% tablerow pair in row %}
          {{ pair[1] }}
        {% endtablerow %}
    {% endif %}
  {% endfor %}
</table>



### Eindrücke
<div class="gallery" data-columns="3">
	<img src="/images/projects/flowerbeds/a1_belle_isis.jpg">
	<img src="/images/projects/flowerbeds/a1_caprioloata.jpg">
	<img src="/images/projects/flowerbeds/a1_koenigin_von_daenemark.jpg">
	<img src="/images/projects/flowerbeds/a1_mme_legras_de_st_germain.jpg">
	<img src="/images/projects/flowerbeds/a3_schwefelrose.jpg">
	<img src="/images/projects/flowerbeds/a4_paeonienrose.jpg">
	<img src="/images/projects/flowerbeds/a4_splendens.jpg">
	<img src="/images/projects/flowerbeds/a4_triginitipetala.jpg">
	<img src="/images/projects/flowerbeds/a7_louise_odier.jpg">
	<img src="/images/projects/flowerbeds/a8_rosa_gallica.jpg">
	<img src="/images/projects/flowerbeds/a10_belle_de_crecy.jpg">
</div>


## Weitere Informationen

Vollständige [Liste der Rosen](/rosenliste)

[Blogeinträge über Rosen](/rosenblogindex)

[Wild- und Heilpflanzen im Rosengarten](/project/begleitpflanzen)

[Artenvielfalt im Rosengarten](/project/artenvielfalt)
