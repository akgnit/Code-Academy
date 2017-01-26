Another way of modifying the position of an element is by setting its position to absolute.

When an element's position is set to absolute, all other elements on the page will ignore the element and act like it is not present on the page.

div.description {
  background-color: #1D09AF;
  width: 50px;
  height: 50px;
  position: absolute;
}
Unlike the relative value, the code in the example is valid. The div will be pinned down to its current position. Unfortunately, if offset properties aren't specified, it's possible for the div's content to overlap with other content on the page, especially since other elements with ignore the div.

Offset properties can be set in order to avoid this problem. The specific offset values will depend on what makes the best sense for the content of a web page.

div.description {
  background-color: #1D09AF;
  width: 50px;
  height: 50px;
  position: absolute; 
  left: 250px;
}
Instructions

1.
In style.css, set the position inside of the .header selector to absolute. Scroll up and down the web page. What do you notice?

2.
Next, add a top and left offset properties and set them to 0 pixels.