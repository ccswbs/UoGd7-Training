# Headings that Expand and Collapse

Start with content that has a heading, e.g.

```markup
<h2>Section Title</h2>

<p>Section text here</p>
<p>More text here</p>
```

To make the section collapsible, it needs to be wrapped in `div` tags like this:

```markup
<div>
<p>Section text here</p>
<p>More text here</p>
</div>
```

After you've put the content in a div, give that div the class name `collapse` and a unique ID:

```markup
<div class="collapse" id="uniqueID">
<p>Section text here</p>
<p>More text here</p>
</div>
```

Now turn your section title into a link with the following code:

```markup
<h2><a href="#uniqueName" class="collapsed" data-toggle="collapse">Section Title</a></h2>
```

Note that `href` has to equal the unique ID of the div. This is so the link, when clicked, knows which div it's supposed to expand or collapse. So if you want multiple divs on the page that can be expanded or collapsed, each one must have a unique ID.

**Note:** If you want a section to be expanded by default when a page loads instead of hidden/collapsed, rewrite the link heading code as follows:

```markup
<h2><a href="#uniqueName" data-toggle="collapse">Section title here</a></h2>
```

That is, remove the code `class=collapsed` \(when you include `class=collapsed`, it makes the link show up with a "Plus" icon to indicate the content can be expanded. This "Plus" icon changes to a "Minus" when the content is expanded\). You also need to change the section's `div` code from:

```markup
<div class="collapse">
```

to:

```markup
<div class="collapse in">
```

## Markup for complete, working example:

```markup
<h2><a href="#sec0" data-toggle="collapse">This section expanded by default</a></h2>
<div class="collapse in" id="sec0">
<p>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. </p>
</div>

<h2><a href="#sec1" class="collapsed" data-toggle="collapse">Section One</a></h2>
<div class="collapse" id="sec1">
<p>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. </p>
</div>

<h2><a href="#sec2" class="collapsed" data-toggle="collapse">Section Two</a></h2>
<div class="collapse" id="sec2">
<p>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. </p>
</div>

<h2><a href="#sec3" class="collapsed" data-toggle="collapse">Section Three</a></h2>
<div class="collapse" id="sec3">
<p>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. </p>
</div>
```

If you'd like to add a button that toggles multiple sections at the same time, you need to add one more class to each `div`. For this example, we'll call the class `collapse-all` though you can use whatever name you prefer:

```markup
<h2><a data-toggle="collapse" data-target="#section1" href="#section1">Section 1 title here</a></h2>
<div class="collapse collapse-all" id="section1">
    <p>Section 1 text here</p>
</div>

<h2><a data-toggle="collapse" data-target="#section2" href="#section2">Section 2 title here</a></h2>
<div class="collapse collapse-all" id="section2">
    <p>Section 2 text here</p>
</div>

<h2><a data-toggle="collapse" data-target="#section3" href="#section3">Section 3 title here</a></h2>
<div class="collapse collapse-all" id="section3">
    <p>Section 3 text here</p>
</div>
```

The code for the button would look like this:

```markup
<button aria-controls="section1 section2 section3" aria-expanded="false" class="btn btn-primary" data-target=".collapse-all" data-toggle="collapse" type="button">Your button text here</button>
```

For `aria-controls`, list all the `div` IDs you want the button to control. For `data-target`, use the class `collapse-all` (or whatever name you chose - it just needs to be the same for each `div`). So the complete code would look something like this:

```markup
<button aria-controls="section1 section2 section3" aria-expanded="false" class="btn btn-primary" data-target=".collapse-all" data-toggle="collapse" type="button">Your button text here</button>

<h2><a data-toggle="collapse" data-target="#section1" href="#section1">Section 1 title here</a></h2>
<div class="collapse collapse-all" id="section1">
    <p>Section 1 text here</p>
</div>

<h2><a data-toggle="collapse" data-target="#section2" href="#section2">Section 2 title here</a></h2>
<div class="collapse collapse-all" id="section2">
    <p>Section 2 text here</p>
</div>

<h2><a data-toggle="collapse" data-target="#section3" href="#section3">Section 3 title here</a></h2>
<div class="collapse collapse-all" id="section3">
    <p>Section 3 text here</p>
</div>
```
