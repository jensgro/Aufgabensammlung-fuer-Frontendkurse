# Individuelle Checkboxen und Radio-Buttons

Formulare zu gestalten ist sehr schwer. Manche Designidee kann man nicht direkt erledigen. Man muss stattdessen Umwege gehen und sich einen Trick ausdenken.

Checkboxen und Radiobuttons kann direkt nicht gestalten. Versuchen Sie es mal:

````html

<div>
    <input type="checkbox" id="my-checkbox-1" name="check1">
    <label for="my-checkbox-1">Meine Checkbox 1</label>
</div>
<div>
    <input type="checkbox" id="my-checkbox-2" name="check2">
    <label for="my-checkbox-2">Meine Checkbox 2</label>
</div>
<div>
    <input type="radio" id="my-radio-1" name="radio1">
    <label for="my-radio-1">Mein Radiobutton 2</label>
</div>
<div>
    <input type="radio" id="my-radio-2" name="radio1">
    <label for="my-radio-2">Mein Radiobutton 2</label>
</div>
````

Als CSS bietet sich bpw. an:

````css
input[type="checkbox"] {
    background-color: red;
    width: 20px;
    height: 20px;
}
input[type="radio"] {
    background-color: blue;
    border: 2px solid red;
    width: 30px;
    height: 30px;
}
````
Probieren Sie das einfach mal aus und spielen Sie mit unterschiedlichem CSS, gerne auch mit anderen Formularelementen.

Wenn man aber nicht das Formularelement, sondern **das assoziierte Label** gestaltet (und das Formularelement versteckt...), dann kann man [ziemlich tolle Designs](https://codepen.io/jensgro/full/yLMQdNQ) machen.

![interessante Designs für Checkboxen und Radiobuttons](checkboxes-radios.png)

Das Verstecken eines Formularelementes geht vorzugsweise so:

````css
[type="checkbox"],
[type="radio"]{
  position: absolute;
  left: -9999px;
  width: 0;
  height: 0;
  visibility: hidden;
}
````
Der Vorteil dieser Methode ist, dass das Formularelement für Screenreader noch voll zugänglich ist, wir es aber 
Der Vorteil dieser Methode ist, dass das Formularelement für Screenreader noch voll zugänglich ist, Sehende es aber nicht wahrnehmen. Ein ``display: none`` hätte das Formularelement auch vor Screenreadern versteckt und das Element wäre nicht anwählbar. Unsere Seite wäre nicht zugänglich, für Screenreadernutzer nicht nutzbar.
