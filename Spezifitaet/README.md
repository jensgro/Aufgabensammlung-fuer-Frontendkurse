# Was kommt am Ende raus?

````
    <h1 class="specificity">Beispiel Headline</h1>
````

````
    h1.specificity:not(#spezi) { color: blue;}
    h1.specificity:not(.spezi) { color: maroon;}
    h1.specificity:not(h1#spezi) { color: yellow;}
    h1.specificity { color: #000;}
    .specificity { color: green;}
````
