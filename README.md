# tachyons-toggle

Easily perform hiding/displaying an element with an input checkbox. This is great for composing any type of popovers or modals that should remain visible until the user actively hides it.

```
<input type="checkbox" class="toggle-checked" />
<div class="toggle-target"> Hidden until the checkbox is clicked on</div>
```

## Example use:

An example modal demo can be viewed on this [Codepen](https://codepen.io/pbobak/pen/LqbQwd). The trick is to use multiple `<label>` elements with matching `for=""` attributes to change the `checked` state of the input element.
