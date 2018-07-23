---
author: stefan.stojanovic

levels:
  - beginner
  - basic

type: normal

category: must-know

stub: true

tags:
  - deep

links:
  - '[CodePen: mark Element](https://codepen.io/enkidevs/pen/GBrJdP){code}'
  - '[CodePen: u Element ](https://codepen.io/enkidevs/pen/OwWVBe){code}'
  - '[MDN docs for u](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/u){website}'
  - '[MDN docs for mark](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/mark){website}'
  - '[MDN docs for global attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes){website}'

---
# Editing (u, mark)
---
## Content

### `<mark>` 

Next, the `<mark>`, or the **Mark Text** element is used to specify that some text is marked or highlighted.

Example:
```
<p>Highlight this
<mark>important</mark>
text in this paragraph.</p>
```
Result:

##### --> editing-elements-mark.svg

![View CodePen](https://codepen.io/enkidevs/pen/GBrJdP)

The text within the `<mark>` element is usually rendered with a yellow background.

The `<mark>` element is often used to indicate a part of the text of the document that is relevant to the user's search.

Also, when `<mark>` is used within a `<q>` or `<blockquote>` element it indicates that that text is important even though it is not marked by the original author as important. This is like highlighting important text from a book with a marker/highlighter.


### `<u>` 

Last but not least, the `<u>`, or the **Unarticulated Annotation** element is used to indicate that some text should be rendered differently from the rest of the text in a way that indicated non-textual annotation. 

Example:
```
<p>You could use this element 
to highlight <u>speling</u>
mistakes, so the writer
can <u>corect</u> them.</p>
```
Result:

##### --> editing-elements-u.svg

![View CodePen](https://codepen.io/enkidevs/pen/OwWVBe)

The content of the `<u>` element is usually rendered as underlined. Nevertheless, you can change this by using the appropriate CSS styling. (`text-decoration; underline`)

**Note:** The `<u>` element used to be called the `Underline` element before when it was only used to underline text. If you wish to set some text as underline, you should not use the `<u>` element to style it but rather the appropriate CSS properties.

Also, when using the `<u>` element you should give it a different style than underlined because users may confuse them with hyperlinks.

The `<u>` element is often used to annotate spelling errors, proper nouns and/or names in Chinese, and other annotations.

---
## Practice

Underline the word "mispell": 

```
<p>
  Try not to 
  <tag>mispell</tag>
  the word "misspell".
</p>
```

tag = ???

Highlight "100 laps" within the blockquote: 

```
<blockquote>
<p>
  "I just ran 
  <tag>100 laps</tag> 
  and I'm not even tired."
</p>
<cite>Bobby the Kid</cite>
</blockquote>
<p>
  What Bobby the Kid doesn't share
  is that a lap around that tree
  is only 10 feet.
</p>
```

tag = ???

* u
* mark
* cross
* out
* under
* underline
* highlight
* high

---
## Revision

Match these elements with their meaning: 

???: defines text that should be styled differently than the rest of the text, such as misspelled words. 
???: defines text that should be highlighted.

* u
* mark
* strike
* delete
* cross
* highlight
