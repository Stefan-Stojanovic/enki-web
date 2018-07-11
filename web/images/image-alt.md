---
author: stefan.stojanovic

levels:
  - beginner
  - basic

type: normal

category: must-know

standards:
  web.embed-media.0: 10

aspects:
  - introduction
  - workout
  - obscura

links:
  - '[Documentation on MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img){documentation}'
  - '[Official documentation on w3.org](https://www.w3.org/TR/2011/WD-html5-author-20110705/the-img-element.html#dom-img-alt){documentation}'

---
# Image Alt
---
## Content

All image `<img>` elements are encouraged to use `alt` attributes which specifies alternate text for the image.

Example:
```
<img src="rainforest.pngrainforest.jpg"
    alt="Beautiful rain forest
         thick with trees">
```
##### --> image-alt.svg

![View CodePen](https://codepen.io/enkidevs/pen/JBjqRb)

In the example above, if for some reason the browser doesn't show the `rainforest.png` image, the `alt` attribute will display the `Beautiful Rainy Forest` text instead.

Using the `alt` attribute is important for every `img` element for page validation and to help support screen readers that will read the text description to those that are visually impaired.

The `alt` attribute can also be left empty and completely valid as this is helpful for indicating that the image is not a key part of the content:
```
<img src="background-image.png"
      alt="">
```

If your `alt` attribute needs to contain acronyms (like "USA"), you would write it as to prevent screen readers from trying to read:
```
`<img src="usa-map.jpg"
    alt="United States of America map">`
```

The reason is, you want to prevent screen readers from reading the any acronyms as single words like: "Usa map".

---
## Practice

What is a best way to treat alt tags for images that are used in the interface and does not contain useful content for the user?

???

* Use an empty alt attribute.
* Write the description only in lowercase.
* Write the description only in uppercase.
* Don't use an alt attribute.

---
## Revision

Which description(s) of using image alt attributes is not true:

???

* Image will not display properly without an alt.
* Required on every image for page validation.
* Important to help support screen readers.
* Useful for webpage viewer when image path is broken.
* Linked image descriptions should be of the destination and not the image itself.


---
## Quiz

### Do you know the best way to write acronyms (like "USA") within image alt attribute?

Hint: The best way helps screen readers read the alt properly as it prevents "ITS in the US" from being read as "It’s in the us".

`<img src="usa-map.jpg" alt="______">`

???

* U S A
* USA
* usa
* U.S.A
* U-S-A
* "U""S""A"
