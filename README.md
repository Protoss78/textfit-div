[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Protoss78/textfit-div)

# textfit-div
A web component that uses <a href="https://github.com/STRML/textFit">STRML/textFit</a> to fit the text size to the available space. When the parent is resized, the text size is adjusted accordingly.
Important: Make sure that textfit-div is put into a container that has an actual size.

Example:
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../iron-flex-layout/iron-flex-layout-classes.html">
    <link rel="import" href="textfit-div.html">
    <custom-style>
        <style is="custom-style" include="iron-flex">
            .fullHeight {
                height: 90%;
                width: 90%;
            }

            paper-card {
                height: 450px;
                width: calc(100% - 2em);
                margin: 1em;
            }
        </style>
    </custom-style>
    <div id="container">
      <next-code-block></next-code-block>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
<paper-card>
    <textfit-div class="fullHeight flex"
                 text="A little bit more text to showcase an extreme sample with multi-line support enabled to demonstrate wrapping capabilities"
                 horizontal-center multi-line></textfit-div>
</paper-card>
```
