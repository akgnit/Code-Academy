All HTML elements can be classified as one of the following: inline elements or block-level elements.

Inline elements - elements that display inline with text, without disrupting the flow of the text (like links).
Block-level elements - elements that use an entire line of space in a web page and disrupt the natural flow of text. Most of the common HTML elements are block-level elements (headings, paragraphs, divs, and more).
In CSS, you can change the default behavior of elements with the display property. Why is this useful?

Modifying the display property of an element can help achieve a desired layout for a web page. The display property can take on one of four values:

inline - causes block-level elements (like a div) to behave like an inline element (like a link).
block - causes inline elements (like a link) to behave like a block element (like a div).
inline-block - causes block-level elements to behave like an inline element, but retain the features of a block-level element.
none - removes an element from view. The rest of the web page will act as if the element does not exist.
It's common to use the display property to create a navigation bar from list items, like so:

<ul>
  <li>Home</li>
  <li>Products</li>
  <li>Settings</li>
  <li>Inbox</li>
</ul>
li {
  display: inline;
}
In the example above, the block-level list items will now behave as inline elements. The result will be list items appearing on the same line, like a navigation bar.

Instructions

1.
In style.css, set the display property of the list items to inline-block.
