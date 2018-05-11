## Headings that expand and collapse sections

Start with content that has a heading, e.g.

```HTML
<h2>Section Title</h2>

<p>Section text here</p>
<p>More text here</p>
```

To make the section collapsible, it needs to be wrapped in `div` tags like this:

```HTML
<div>
<p>Section text here</p>
<p>More text here</p>
</div>
```

After you've put the content in a div, give that div the class name `collapse` and a unique ID:

```HTML
<div class="collapse" id="uniqueID">
<p>Section text here</p>
<p>More text here</p>
</div>
```

Now turn your section title into a link with the following code:

```HTML
<h2><a href="#uniqueName" class="collapsed" data-toggle="collapse">Section Title</a></h2>
```

Note that `href` has to equal the unique ID of the div. This is so the link, when clicked, knows which div it's supposed to expand or collapse. So if you want multiple divs on the page that can be expanded or collapsed, each one must have a unique ID.

**Note:** If you want a section to be expanded by default when a page loads instead of hidden/collapsed, rewrite the link heading code as follows:

```HTML
<h2><a href="#uniqueName" data-toggle="collapse">Section title here</a></h2>
```

That is, remove the code `class=collapsed` (when you include `class=collapsed`, it makes the link show up with a "Plus" icon to indicate the content can be expanded. This "Plus" icon changes to a "Minus" when the content is expanded). You also need to change the section's `div` code from:

```HTML
<div class="collapse">
```
to:

```HTML
<div class="collapse in">
```

### Markup for complete, working example:

```HTML
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
