# Aufgabensammlung für Frontendkurse

Viele der hier gesammelten Aufgaben stammen aus Codepen. Eine beiligende README-Datei informiert dann über die Quelle.


Zur Unterstützung bei der Bearbeitung der Aufgaben habe ich **[hilfreiche Links](hilfreiche-links.md)** gesammelt.

## Boxmodell

- Entferne [die Lücke unterhalb des Bildes](Boxmodell/textunterlaenge-und-bilder) im zweiten Container.
- Gib den [unterschiedlichen Inline-Elementen](Boxmodell/zeilenboxen-und-display-eigenschaft) ein vertikales Padding und Margin, das wirklich eine Auswirkung hat.
- Ein Spezialfall in der internen Logik von CSS sind [kollabierende Margins](kollabierende-margins/index.html). Die CSS-Arbeitsgruppe des W3C sagt heute, sie würden diese Entscheidung heute nicht mehr treffen. Eine knappe Erklärung gibt es unter [collapsing margins](https://www.mediaevent.de/css/margin.html) bei Mediaevent.

## Selektoren

- Gestalte die [Tabelle der 2. Fussball-Bundesliga](Selektoren/bundesliga-tabelle) mit CSS. 
  * Idealerweise musst Du dafür keine Änderungen am HTML vornehmen. Du kannst die existierenden Klassen nutzen, aber auch auf sie verzichten. 
  * Welche Vor- und Nachteile hätte dieser Verzicht?
- Gestalte [einen einfachen Text](Selektoren/text-mit-selektoren-gestalten/) nur mit Selektoren.

## Kaskade

Welche Farbe haben [diese beiden](Kaskade/README.md) `DIV`s?

## Spezifität

Schau Dir [die folgenden Regeln an](Spezifitaet/README.md) und bestimme das Ergebnis.

## Dokumentenfluss

[Mit diesem Beispiel](dokumentenfluss/) kannst Du die Effekte von Positionierungen, negative Margins, z-index und Floats überprüfen. Die Datei ist auch [auf Codepen](https://codepen.io/jensgro/pen/jCmbI) erreichbar.

## Positionierung

[Einsteigertest](Positionierung/test-positionierung) über die Grundbegriffe der Positionierung. Bitte genau auf die Dimensionen und Farben achten. Wer mag und schnell genug ist, kann gerne die Zusatzaufgabe lösen.

## Floats

[Spiele](Floats/floating/) ein wenig mit der Float-Technik. 

## Layout (Grid) erstellen

Arbeite mit unterschiedlichen Methoden zur Erstellung eines Layout mit dieser [sehr einfach gehaltenen Vorlage](Layout-erstellen/ein-einfaches-grid-bauen).

## Module erstellen

- [Text über ein Bild schieben](Module-erstellen/texte-ueber-bilder-schieben)
- [Eine Card](Module-erstellen/cards-1)  mit interaktiven Elementen
- [Eine Card](Module-erstellen/cards-2)  mit einem Bild, das bei `:hover` nach rechts rutscht

## [Formulare](Formulare/README.md)

- Erstelle und gestalte [bitte eines oder mehrere dieser Formulare](Formulare/README.md#bitte-eines-oder-mehrere-dieser-formulare-nachbilden)
- Spiele ausserdem mit [Checkboxen und Radiobuttons](Formulare/README.md#individuelle-checkboxen-und-radio-buttons) herum. Die kann man zwar nicht direkt gestalten, aber es gibt Mittel und Wege, sie interessanter zu machen. 

Grundlegende Infoseiten dazu:

- https://developer.mozilla.org/de/docs/Learn/Forms
- https://wiki.selfhtml.org/wiki/HTML/Tutorials/Formulare 

## Flexbox

- Erstelle bitte [ein dreispaltiges Layout](todo-dreispaltiges-flexbox-layout) mit Hilfe dieser Vorlage.
- [Eine horizontale Navigation](todo-hauptnavigation-mit-flexbox) ist ein klassischer Anwendungsfall für Flexbox. Bitte die halb gestaltete Liste mit Flexbox transformieren und mit den Eigenschaften experimentieren.
- Arrangiere die Beispielcontainer [in einem Beispiel-Layout](ein-einfaches-grid-bauen). Denk daran: die Layoutcontainer sind wie ein Setzkasten. In diese Container kommt erst der darzustellende Inhalt. Die Container selber bereiten nur den Platz vor.
- [Erstelle eine Card](cards-1)  mit interaktiven Elementen.
- [Erstelle eine Card](cards-2)  mit einem Bild, das bei `:hover` nach rechts rutscht.
- [Diese hübschen Kommentarboxen](todo-kommentare-mit-wechselnden-richtungen) müssen als Erstes mit Flexbox layoutet werden. In einem zweiten Schritt sollen die Ausrichtungen der Bilder abwechselnd links und rechts sein.
- Es ist eine beliebte Herausforderung, dass [ein Footer einer Seite immer zumindest am Ende des Viewports platziert sein soll](todo-sticky-footer-mit-flexbox), auch wenn nur wenig Inhalt existiert. Früher benötigte man dafür eine passende Struktur und musste ein wenig tricksen. Mit Flexbox geht dies ganz einfach. Also ran und die Lösung finden!
- Bring [diese Teasercontainer](todo-teaser-mit-gleicher-hoehe) in einem Grid unter und formatiere sie auf gleiche Höhe. Es soll sich bei Bedarf automatisch eine neue visuelle Zeile bilden.
- Eine sehr einfache Aufgabe: Bitte diese schon in einem kleinen Grid platzierten [Visitenkarten gestalten](todo-visitenkarten).
