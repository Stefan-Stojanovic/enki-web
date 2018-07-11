---
author: stefan.stojanovic

levels:
  - beginner
  - basic

type: normal

category: must-know

standards:
  web.html-forms.2: 10
  web.embed-media.0: 10

aspects:
  - introduction
  - workout
  - obscura

links:
  - '[MDN docs for image buttons](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/image){website}'
  -

---
# Image Button
---
## Content

The HTML input form of type `image` is used to create a submit button with a graphical image instead of the default text.

Example:
```
<form
  action="/page.php">
  Full name:
    <input type="text"
      name="fname">
  <input type="image"
    src="send.png"
    alt="Submit"
    width="100" height="100">
</form>
```

##### form-image-button.svg

![View CodePen](https://codepen.io/enkidevs/pen/vrvvJO)

In the example above, the input type is set as `image`. The image source is currently in the same folder as the HTML page with the filename `send.png`. The `width` and `height` properties are set in pixels, both to `100` by `100`.

---
## Practice

Write the form code that creates an image button.

`<??? ???="???" ???="button.png" alt="Send" >`

* input
* type
* image
* src
* alt
* name
* submit

---
## Revision

What code is used to replace a form's submit button with an image?

???

* `<input type="image" src="button.png" >`
* `<img type="submit" src="button.png" >`
* `<input type="submit" src="button.png" >`
* `<img type="image" src="button.png" >`


---
## Quiz

### How much do you know about image buttons?

Which attribute is not a valid image button attribute for overriding default form behaviors?

* formoverride
* formaction
* formmethod
* formnovalidate
* formtarget
* formenctype
