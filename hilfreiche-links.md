# Hilfreiche Links

  - [Referenzen](#referenzen)
  - [Infoseiten](#infoseiten)
  - [Tools](#tools)
  - [Validierung](#validierung)
  - [Blindtexte und Platzhalterbilder](#blindtexte-und-platzhalterbilder)
  - [SVGs](#svgs)
  - [Vergleich zwischen zwei Browser-Normalisierungen](#vergleich-zwischen-zwei-browser-normalisierungen)
  - [Das Boxmodell](#das-boxmodell)
  - [Kollabierende Margins](#kollabierende-margins)
  - [Sammlungen von Beispielen zur Inspiration auf CodePen](#sammlungen-von-beispielen-zur-inspiration-auf-codepen)
  - [Bilder beschneiden](#bilder-beschneiden)
  - [Bilder responsive machen](#bilder-responsive-machen)
  - [Bilder responsive einbinden](#bilder-responsive-einbinden)

## Referenzen

Für die Suche nach HTML-Elementen und CSS-Eigenschaften eignet sich [MDN](https://developer.mozilla.org/de/) immer in besonderem Maße. Ich bevorzuge hingegen [devdocs](https://devdocs.io/). Das ist eine einheitliche, schnell ladende Oberfläche für sehr viele APIs. Die Seiten von MDN werden auch genutzt. Allerdings (logischerweise) nur in der englischsprachigen Variante. 

- [devdocs.io](http://devdocs.io) - alle wichtigen Dokumentationen für Webtechnologien an einer Stelle 
- [MDN](https://developer.mozilla.org/de/) - Dokumentationen zu HTML, CSS und JavaScript von Mozilla (englisch und deutsch)
- [SELFHTML](http://wiki.selfhtml.org) - deutschsprachige Doku zu HTML, CSS und JavaScript 
- [Codrops CSS-Referenz](https://tympanus.net/codrops/css_reference/)

## Infoseiten 

- [CSS-Tricks Almanach](https://css-tricks.com/almanac/)
- [devhints](https://devhints.io/) - Cheatsheets
- [Frontend Development Resources](http://jensgro.github.io/Frontenddevelopment-Resources/) - meine Linksammlung von wichtigen Tools und Quellen
- [das Periodensystem der HTML-Elemente](https://codepen.io/jensgro/full/rXegzj)
- [Mediaevent](https://www.mediaevent.de/)
- [SELFHTML](https://wiki.selfhtml.org/)

## Tools

- [Farbverläufe erstellen](https://omatsuri.app/gradient-generator) - mit Codeausgabe 
- [animate.css - fertige Animationen zum Kopieren](https://daneden.github.io/animate.css/) 
- [animista - eine weitere Variante, um fertige Animationen zu kopieren](http://animista.net/)  
- [Specificity Calculator](https://codepen.io/jensgro/full/LEcGF)
- [Flexbox Playground 1](https://codepen.io/jensgro/full/kXwjgZ)
- [Flexbox Playground 2](https://codepen.io/jensgro/full/grRLqY)

## Validierung

- [W3C-Validator](http://validator.w3.org/)
- [ein weiterer Validator](https://validator.nu/)
- [Valide ist nicht zwangsweise semantisch korrekt](https://gist.github.com/jensgro/7303631)

## Blindtexte und Platzhalterbilder

-  Blindtexte kannst Du Dir im [Blindtextgenerator](http://www.blindtextgenerator.de/) in unterschiedlichen Sprachen zusammenstellen. Auch in Deutsch!
-  Eine Auswahl an kostenlosen Platzhalterbildern für Entwürfe bietet [meine Codepen-Seite](https://codepen.io/jensgro/full/HFnsE).
-  Auf Codepen findest Du [unzusammenhängende Blindtexte](https://codepen.io/jensgro/pen/yactj?editors=1000) und einen sehr alten Artikel von mir als Blindtext: [Webseiten sind keine Gemälde](https://codepen.io/jensgro/pen/vFagC?editors=1000).

## SVGs

- [SVGs für eigene Entwürfe](https://codepen.io/jensgro/pen/LYPLEvE)
- [weitere, sehr einfach gehaltene SVGs](https://codepen.io/jensgro/pen/yzryMN) für eigene Entwürfe - sie können diesmal einfacher einzeln herauskopiert werden
-  SVG-Illustrationen findest Du auf [undraw](https://undraw.co/illustrations).

## [Vergleich zwischen zwei Browser-Normalisierungen](vergleich-normalize-css-und-reboot-css/html-kitchensink-normalize/index.html)

Im Gegensatz zu einem Reset-CSS, das alle Unterschiede in einem Browser-CSS auf ein gemeinsames "Null" setzt, definieren Normalisierungs-CSS für alle Browser gemeinsame Basis-Gestaltungen. Das bekannteste und quasi die "Urmutter" ist "Normalize". Für Bootstrap v4 machte das Bootstrap-Team davon einen Fork und entwickelte es mit eigenen Ideen weiter. Das Ergebnis ist "Reboot". [Diese Seite](vergleich-normalize-css-und-reboot-css/html-kitchensink-normalize/index.html) stellt beide nebeneinander ([auch auf Codepen](https://codepen.io/jensgro/full/VwZNmaM)). 

Noch beeindruckender ist [der Vergleich unterschiedlicher Ansätze](https://codepen.io/jensgro/full/xBxqer) für Normalisierung oder Browser-Reset auf Codepen. 

## Das Boxmodell

Wenn man nicht aufpasst, kann man mit hover-Styles [in ein Problem mit dem Boxmodell](https://codepen.io/jensgro/pen/YBJMyQ) reinlaufen.

Das Boxmodell als [3D-Modell](https://codepen.io/argyleink/full/BaLedvd) ist ganz unterhaltsam. Aber wahrscheinlich versteht man es [in der 2D-Ansicht](https://codepen.io/benrobyg/full/XBPNbx) viel besser.

## [Kollabierende Margins](kollabierende-margins/index.html)

Der Umgang mit margins (also den Aussenabständen eines Elements) ist speziell. Neben der Regel für Elemente, die nicht als Blockelement formatiert sind (da ziehen die vertikalen Margins nicht), verwirren auch immer die "kollabierenden Margins". ([Codepen-Version](https://codepen.io/jensgro/full/OKjVrX))

Wenn zwei normal im Dokumentenfluss befindliche Elemente aufeinandertreffen, addieren sich die Margins **nicht**. Es gewinnt die größere Margin. Bei gleichen wird eine von beiden genommen.
Dies ändert sich, wenn zwei Floats aufeinandertreffen. Denn dann wiederum addieren sich die Margins.

## Sammlungen von Beispielen zur Inspiration auf CodePen

- [SVG](https://codepen.io/collection/nLjVea/)
- [Flexbox](https://codepen.io/collection/XgxakO/) 
- [Transformationen und Animationen](https://codepen.io/collection/XLjYoE/) 
- [custom properties](https://codepen.io/collection/naydzK/) (vulgo: CSS Variablen)

## Bilder beschneiden

CodePen mit zwei Techniken zur [Einbindung und Beschneidung großer Bilder](https://codepen.io/jensgro/pen/JjPJePE?editors=0100)

## Bilder responsive machen

Jedem Bild, das sich über wechselnde Breiten skalieren soll, sollte diese Klasse mitgegeben werden (der Klassenname ist natürlich individuell wählbar):

````
    .flexible {
        width: 100%;
        max-width: 100%;
        height: auto;
    }
````

## Bilder responsive einbinden

- [Mein einführender Artikel von 2014](http://webkrauts.de/artikel/2014/der-neue-standard-fuer-responsive-bilder)
- [A Guide to Responsive Images with Ready-to-Use Templates](https://medium.freecodecamp.org/a-guide-to-responsive-images-with-ready-to-use-templates-c400bd65c433)
- [Responsive Images 101](https://cloudfour.com/thinks/responsive-images-101-definitions/) (eine umfangreiche und tolle Serie)

