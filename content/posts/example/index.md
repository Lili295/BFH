+++
title = "Mandala"
date = "2023-11-14"
draft = false
pinned = false
tags = ["jewlery", "DIY", "homemade"]
image = "/img/default-image.jpg"
description = "Mandala is for everyone"
footnotes = "In der Fusszeile können zum Beispiel Bildquellen angegeben werden. Dieser Text ist abgetrennt durch eine Linie und etwas kleiner."
+++
<!--StartFragment-->

The main purpose of coloured pencils is to draw or colour in per example mandalas. All you need to do so is some coloured pencils and a paper or a mandala. In the western culture mandalas are mainly used to relax. And the best part about colouring a mandala is, that it actually also has some psychological benefits to the person doing it. Here’s a list of some of the benefits of colouring mandalas: 

* Stimulates creativity and concentration 
* It combines creativity with logic 
* Acts soothing 
* Helps fostering attentiveness 
* Helps to be mor focused in your job or in your studies and not get distracted that easily 
* Supports inner peace and calmness 
* Helps relieving stress in your everyday life 
* Acts as a form of meditation and therefore helps to forget the world around you for a moment
* It fosters the feeling of balance due to the way the forms and structures are arranged

<!--EndFragment-->

![Der Alt-Text wird jeweils als Bildunterschrift angezeigt.](/img/default-image.jpg)

**Empfehlung für Bilder**: Meist empfiehlt sich, ein Bild ganz zuoberst im `Inhalt`-Feld einzufügen. Zusätzlich sollte man dieses auch im `Bild`-Feld angeben, damit es in der Blogübersicht erscheint.

### Tipps zu Bildgrössen

Ein Richtwert für Bilder ist, dass diese wenn möglich nicht grösser als `400kb` sein sollten. Man kann sie so verkleinern, dass die Breite höchstens `1200px` gross ist. Dies ist für die meisten Bildschirme mehr als genug.

### Bildunterschrift

Wenn bei einem Bild ein `ALT TEXT` erfasst wird, so wird dieser als Bildunterschrift im Artikel angezeigt.

## Horizontale Linie

Eine Horizontale Linie kann man entweder durch ein `<hr>` einfügen oder indem man im `Markdown`-Modus drei Striche `---` einfügt. So sieht die Linie aus:

- - -

## Lead

{{<lead>}}
Oft haben Artikel unterhalb des Haupttitels einen einführenden Lead, der etwas grösser dargestellt wird.
{{</lead>}}

`{{</*lead*/>}}`\
Ein Lead steht zwischen zwei solchen Blöcken.\
`{{</*/lead*/>}}`

## Kasten

{{<box>}}
In dieser Box können Texte, Bilder, Videos oder andere Inhalte dargestellt werden.
{{</box>}}

`{{</*box*/>}}`\
Der Inhalt einer Box muss wie hier von zwei Blöcken umgeben werden.\
`{{</*/box*/>}}`

{{<box title="Ausklappbare Box">}}
Wird ein Titel angegeben, so kann die Box ausgeklappt werden.

Dies eignet sich auch für längere Inhalte.

![](/img/default-image.jpg)

Auch Bilder können in eine Box gepackt werden.
{{</box>}}

`{{</*box title="Ausklappbare Box"*/>}}`\
Wird ein Titel angegeben, so kann die Box ausgeklappt werden.\
`{{</*/box*/>}}`

## Video, Audio und andere Medien einbetten

Es kann auch `HTML-Code` eingefügt werden. Manchmal geht dies etwas einfacher, wenn man dazu in den `Markdown`-Modus wechselt.

Damit können zum Beispiel Filme, Audiodateien oder Karten eingebettet werden. Meist sind auf den entsprechenden Plattformen (YouTube, Vimeo, Google Maps, etc.) entsprechende Code-Ausschnitte vorbereitet, die man direkt in den Blog einfügen kann. Am besten auf der jeweiligen Plattform nach einem Knopf für `embed` oder `share` suchen.

Bei Videos ist es ideal, wenn sie sich automatisch **an die Bildschirmgrösse anpassen**. Dies geht am einfachsten mit den hinterlegten YouTube- und Vimeo-Codes:

### YouTube einbetten

Einbetten von YouTube-Videos mit dem Code: `{{</*youtube video_id*/>}}`

(Die `video_id` steht bei jedem YouTube-Video in der Browser-URL.)

{{<youtube kQjtK32mGJQ>}}

### Vimeo einbetten

Einbetten von Vimeo-Videos geht mit dem Code: `{{</*vimeo video_id*/>}}`

{{<vimeo 194276412>}}

### Code und Code-Blöcke

Mit dem Code-Symbol `<>` können Wörter auf `diese Art` hervorgehoben werden. Dies wird zum Beispiel für Tastenkombinationen wie `ctrl+s` oder für `Programmiercode` verwendet. Auch Math-Formeln können so ausgedrückt werden: `y = mx + b`.

Für längere solche Abschnitte verwendet man am besten das Code-Block-Symbol. Damit wird ein solcher Block erstellt:

```
const sun1 = "sun" + "il";
const sun2 = "su" + "n" + "il";
sun1 === sun2;
```

## Spass haben

😀 Viel Spass mit deinem Blog!