One way to modify the default position of an element is by setting its position property to relative.

This value allows you to position an element relative to its default position the web page.

div.description {
  background-color: #1D09AF;
  width: 50px;
  height: 50px;
  position: relative;
}
Although the code in the example above instructs the browser to expect a relative positioning of the div, it does not specify exactly where the div should be positioned on the page.

div.description {
  background-color: #1D09AF;
  width: 50px;
  height: 50px;
  position: relative;
  top: 50px; 
  left: 75px;
}
In the example above, the div has been positioned using two of the four offset properties. The valid offset properties are:

top - moves the element down.
bottom - moves the element up.
left - moves the element right.
right - moves the element left.
In the example above, the div will be moved down 50 pixels and to the right 75 pixels. Units for offset properties can be specified pixels, ems, or percentages. Note that offset properties will not work if the position of the element is not set to relative.

Instructions:

1.
In style.css, set the position in .question to relative.

2.
Next, add 240 pixels on to the top of div.question (again, in style.css).