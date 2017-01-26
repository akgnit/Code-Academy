When an element's position is set to absolute, as in the last exercise, that element can still scroll out of view when a user scrolls.

We can fix an element to a specific position on the page (regardless of user scrolling) by setting its position to fixed.

div.navigation {
  position: fixed;
  height: 50px; 
  width: 100%;
}
In the example above, the div will remain fixed to its position no matter where the user scrolls on the page. This technique is used often for navigation bars on a web page.

It's still possible, however, for content (like text) to overlap other content when using this position. One solution is to set an opaque background color for the element.

div.navigation {
  position: fixed;
  background-color: #4BF5FF;
  height: 50px; 
  width: 100%;
}
The opaque background color will prevent any other content on the page from overlapping with any content inside of the div.

Instructions:

1.
In style.css, change the position inside of the .header selector to fixed. Scroll up and down the web page. What do you notice?