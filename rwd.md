# Responsivität

Um eine Seite responsiv zu gestalten, also auf allen zur Verfügung stehnenden Breiten vernünftig aussehen zu lassen, benötigt man eine grundlegende Technik: Media Queries. 

Eine Media Query umfasst einen Codebereich, der **ab** oder **bis zu** einer bestimmten Breite des Viewports gelten soll. Du schreibst bspw:

````
@media (max-width: 800px) {
    .meine-klasse {
        /* Regeln, die nur bis 800px Breite gelten */
    }
}

@media (min-width: 801px) {
    .meine-klasse {
        /* Regeln, die nur ab 801px Breite gelten */
    }
}
````

## Bilder responsive machen

Jedem Bild, das sich über wechselnde Breiten skalieren soll und bei dem die Quelle **nicht** wechseln soll, sollte diese Klasse mitgegeben werden:

````
    .flexible {
        width: 100%;
        max-width: 100%;
        height: auto;
    }
````
Der Klassenname ist natürlich individuell wählbar, dies ist nur ein Vorschlag.

## Bilder responsive einbinden

- [Mein einführender Artikel von 2014](http://webkrauts.de/artikel/2014/der-neue-standard-fuer-responsive-bilder)
- [A Guide to Responsive Images with Ready-to-Use Templates](https://medium.freecodecamp.org/a-guide-to-responsive-images-with-ready-to-use-templates-c400bd65c433)
- [Responsive Images 101](https://cloudfour.com/thinks/responsive-images-101-definitions/) (eine umfangreiche und tolle Serie)

# Interessante Links zu Responsive Webdesign

[Frontenddevelopment-Resources/rwd](http://jensgro.github.io/Frontenddevelopment-Resources/rwd.html)
