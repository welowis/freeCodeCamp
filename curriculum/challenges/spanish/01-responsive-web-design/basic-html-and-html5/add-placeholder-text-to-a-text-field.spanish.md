---
id: bad87fee1348bd9aedf08830
title: Add Placeholder Text to a Text Field
challengeType: 0
videoUrl: ''
localeTitle: Añadir texto de marcador de posición a un campo de texto
---

## Description
<section id="description"> El texto de marcador de posición es lo que se muestra en su elemento de <code>input</code> antes de que su usuario haya ingresado algo. Puede crear texto de marcador de posición de la siguiente forma: <code>&lt;input type=&quot;text&quot; placeholder=&quot;this is placeholder text&quot;&gt;</code> </section>

## Instructions
<section id="instructions"> Establezca el valor de <code>placeholder</code> de <code>placeholder</code> de su <code>input</code> texto en &quot;URL de foto de gato&quot;. </section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Agregue un atributo de <code>placeholder</code> al elemento de <code>input</code> texto existente.
    testString: 'assert($("input[placeholder]").length > 0, "Add a <code>placeholder</code> attribute to the existing text <code>input</code> element.");'
  - text: Establezca el valor de su atributo de marcador de posición en "URL de foto de gato".
    testString: 'assert($("input") && $("input").attr("placeholder") && $("input").attr("placeholder").match(/cat\s+photo\s+URL/gi), "Set the value of your placeholder attribute to "cat photo URL".");'
  - text: El elemento de <code>input</code> terminado debe tener una sintaxis válida.
    testString: 'assert($("input[type=text]").length > 0 && code.match(/<input((\s+\w+(\s*=\s*(?:".*?"|".*?"|[\^"">\s]+))?)+\s*|\s*)\/?>/gi), "The finished <code>input</code> element should have valid syntax.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <input type="text">
</main>

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
