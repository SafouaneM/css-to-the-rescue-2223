

Css tutorial over has

```css

figure:has(figcaption) {
    padding:1em;
    background-color: chocolate;
}

figure:has(figcaption .closed) {
    background-color: #999;
    background-image: repeating-linear-gradient(#bbb,#ddd);
}

figure:has(figcaption .closed) figcaption {
    color: chocolate;
}


figure:has(figcaption .closed) figcaption .closed {
    color: darkcyan;
}

/*!*margin weghalen if h1 has time ~ is ook sterk*/
h1:has(+ time) { 
    margin-bottom: 0;
}

/*dit als p tag heeft en time zit daar in*/
h1:has(+p time) {
    margin-bottom: 0;
}


/*dit is een h1 element + p element die time in zich heeft*/
h1 + p:has(time) {
    
}

/*interactie met een kikker met een input checked het decor*/

body:has(#decor:checked) {
    background-color: green;
}

body:has(#steen:checked) img {
    filter:grayscale(1) contrast(.25);
}

/*dropdown*/
body:has(option[value="red"]:checked) {
    
}

body:has(option[value="red"]:checked) img{
filter:hue-rotate(210deg)
}

body:has(option[value="blue"]:checked ) img:nth-of-type(1) {
    
}

/*has() advanced artikel lezen copium*/

label:has(:checked) {
    background-color: palevioletred;
    accent-color: deeppink;
}

/*inlezen op custom props*/

```