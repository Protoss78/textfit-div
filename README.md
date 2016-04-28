# textfit-div
A web component that uses <a href="https://github.com/STRML/textFit">STRML/textFit</a> to fit the text size to the available space. When the parent is resized, the text size is adjusted accordingly.

API Documentation and a live demo can be found at the <a href="http://protoss78.github.io/textfit-div">component page</a>.

Example:

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
