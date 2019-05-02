# Bootstrap: Typography

Bootstrap is an open-source front-end framework that is used to create responsive webpages.

The Typography classes allow you to style your content beyond default settings. Bootstrap has a global default font size of 14px.

Example classes and elements include:

* `.lead`: creates larger, emphasized text
* `.h1` - `.h6`: creates text that mimics the appearance of headings
* `.small` and `<small>`: creates lighter, secondary text
* `<mark>`: creates highligted text
* `<del>` and `<s>`: creates text with a strikethrough
* `<ins>` and `<u>`: creates underlined text
* `<strong>`: creates bold text
* `<em>`: creates italicized text

## Options for Text Sizes

### Lead

Lead is a class that can increase the size of text. This is very useful when you would like to draw the user's attention to a piece of text that is not a heading. To ensure content is accessible, avoid using heading tags solely to make text appear larger. Heading tags should also be used in logical order.

To implement Lead, add `class="lead"` to an HTML element:

`<div class="lead">Example text.</div>`

What Lead looks like, compared to unstyled text and an `<h2>` heading:

> ![text with lead class compared with unstyled paragraph text and an h2 heading](../.gitbook/assets/lead%20%281%29.png)

### .h1 - .h6 Classes

Bootstrap heading classes \(`.h1` - `.h6`\) create text that has the same visual effect as heading tags. Note that these are not the same as HTML headings and should not be used as such. Like Lead, use these classes for inline text that is not a heading, but needs to be emphasized.

Headings are semantic, while classes are visual.

To implement heading classes, add `class=h[numeral between 1 and 6]` to an HTML element:

`<div class="h1">Example h1 class text</div>`

`<div class="h2">Example h2 class text</div>`

`<div class="h3">Example h3 class text</div>`

`<div class="h4">Example h4 class text</div>`

`<div class="h5">Example h5 class text</div>`

`<div class="h6">Example h6 class text</div>`

What heading classes look like:

> ![example text with h1-h6 bootstrap heading classes](../.gitbook/assets/heading-classes-example%20%282%29.png)

