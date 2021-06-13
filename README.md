# Aufgabensammlung für Frontendkurse

Viele der hier gesammelten Aufgaben stammen aus Codepen. Eine beiligende README-Datei informiert dann über die Quelle.

Der Master-Branch dieses Repo ist immer für die aktuelle Schulung gedacht und wird danach als datierter oder benamter Branch dupliziert.

Zur Unterstützung bei der Bearbeitung der Aufgaben habe ich **[hilfreiche Links](hilfreiche-links.md)** gesammelt. 

## Boxmodell

- Entfernen Sie [die Lücke unterhalb des Bildes](Boxmodell/textunterlaenge-und-bilder) im zweiten Container.
- Geben Sie den [unterschiedlichen Inline-Elementen](Boxmodell/zeilenboxen-und-display-eigenschaft) ein vertikales Padding und Margin, das wirklich eine Auswirkung hat.

## Positionierung

[Einsteigertest](Positionierung/test-positionierung) über die Grundbegriffe der Positionierung.

## Selektoren

Gestalten Sie die [Tabelle der 2. Fussball-Bundesliga](Selektoren/bundesliga-tabelle) mit CSS. Idealerweise müssen Sie dafür keine Änderungen am HTML vornehmen. Sie können die existierenden Klassen nutzen, aber auch auf sie verzichten. 
Welche Vor- und Nachteile hätte dieser Verzicht?

Gestalten Sie [einen einfachen Text](Selektoren/text-mit-selektoren-gestalten/) nur mit Selektoren.

## Kaskade

Welche Farbe haben [diese beiden](Kaskade/README.md) `DIV`s?

## Spezifität

Schauen Sie sich [die folgenden Regeln an](Spezifitaet/README.md) und bestimmen Sie das Ergebnis.

## Floats

[Spielen Sie](Floats/floating/) ein wenig mit der Float-Technik. 

## Layout (Grid) erstellen

Arbeiten Sie mit unterschiedlichen Methoden zur Erstellung eines Layout mit dieser [sehr einfach gehaltenen Vorlage](Layout-erstellen/ein-einfaches-grid-bauen).

## Module erstellen

- Mit dieser Vorlage sollen Sie [Text über ein Bild schieben](Module-erstellen/texte-ueber-bilder-schieben) und das Gesamtkonstrukt auch noch gut aussehen lassen. Nutzen Sie gerne Animationstechniken, um den Text erst bei Überfahren mit der Maus erscheinen zu lassen. 
- [Erstellen Sie eine Card](Module-erstellen/cards-1)  mit interaktiven Elementen.
- [Erstellen Sie eine Card](Module-erstellen/cards-2)  mit einem Bild, das bei `:hover` nach rechts rutscht.

## [Formulare](Formulare/README.md)

Bauen Sie ein Formular, bspw. mit Namen- und Adressfeldern. Sie können es dann später mit CSS gestalten und die Grenzen der Möglichkeiten erfahren. Auf dem beispielhaften Screenshot finden Sie viele Anregungen für interessante Formulare.

## [Card](Card/card.html)

[Ein Teaser](Card/card.html) - neuerdings "Card" genannt - mit grober Gestaltung. Daran sollte herumgespielt werden.

## [Vergleich zwischen zwei Browser-Normalisierungen](vergleich-normalize-css-und-reboot-css/html-kitchensink-normalize/index.html)

Im Gegensatz zu einem Reset-CSS, das alle Unterschiede in einem Browser-CSS auf ein gemeinsames "Null" setzt, definieren Normalisierungs-CSS für alle Browser gemeinsame Basis-Gestaltungen. Das bekannteste und quasi die "Urmutter" ist "Normalize". Für Bootstrap v4 machte das Bootstrap-Team davon einen Fork und entwickelte es mit eigenen Ideen weiter. Das Ergebnis ist "Reboot". [Diese Seite](vergleich-normalize-css-und-reboot-css/html-kitchensink-normalize/index.html) stellt beide nebeneinander ([auch auf Codepen](https://codepen.io/jensgro/full/VwZNmaM)). 

Noch beeindruckender ist [der Vergleich unterschiedlicher Ansätze](https://codepen.io/jensgro/full/xBxqer) für Normalisierung oder Browser-Reset auf Codepen. 

## [Kollabierende Margins](kollabierende-margins/index.html)

Der Umgang mit margins (also den Aussenabständen eines Elements) ist speziell. Neben der Regel für Elemente, die nicht als Blockelement formatiert sind (da ziehen die vertikalen Margins nicht), verwirren auch immer die "kollabierenden Margins". ([Codepen-Version](https://codepen.io/jensgro/full/OKjVrX))

Wenn zwei normal im Dokumentenfluss befindliche Elemente aufeinandertreffen, addieren sich die Margins **nicht**. Es gewinnt die größere Margin. Bei gleichen wird eine genommen.
Dies ändert sich, wenn zwei Floats aufeinandertreffen. DA wiederum addieren sich die Margins.
