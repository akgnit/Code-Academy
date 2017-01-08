The class selector targets all elements of a particular class. It's possible, however, for multiple elements on a web page to share a specific styling, but for one of those elements to differ slightly.

For example, a heading and a paragraph (both with a class of breaking) may need to share the same typeface, but the paragraph may require a styling better suited for paragraphs, as in the following example.

.breaking {
  font-family: Georgia, Times, serif;
}

p.breaking {
  line-height: 1.3em;
}
The example above uses a new selector: p.breaking. What's the difference between the .breaking and p.breaking selectors?

The .breaking selector targets all elements with a class of breaking. The p.breaking selector targets only <p> elements with a class of breaking. This type of selector allows you to be even more specific about a particular element's styling, even when that element must share some styling with other elements.

Unless otherwise specified, the rest of this course will use the element.class selector syntax.
