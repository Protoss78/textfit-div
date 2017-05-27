[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Protoss78/textfit-div)

# textfit-div
A web component that uses <a href="https://github.com/STRML/textFit">STRML/textFit</a> to fit the text size to the available space. When the parent is resized, the text size is adjusted accordingly.

Example:
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="textfit-div.html">
    <style is="custom-style">
      #container {
        display: block;
        height: 400px;
        width: 400px;
      }
    </style>
    <div id="container">
      <next-code-block></next-code-block>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
<textfit-div text="Hello"></textfit-div>
```



```html
<div class="layout horizontal flex wrap">
    <div class="layout horizontal flex">
          <textfit-div horizontal-center vertical-center text="Hey!"></textfit-div>
    </div>
    <div class="layout horizontal flex">
        <textfit-div text="Good Evening!"></textfit-div>
    </div>
</div>
```
