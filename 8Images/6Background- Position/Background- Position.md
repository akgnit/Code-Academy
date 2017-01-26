When a background image is not repeated, its position can be modified with the background-position property.

p {
  background-image: url("#");
  background-repeat: no-repeat;
  background-position: right center;
}
A background image is positioned using a 3 by 3 grid (three rows, three columns), meaning there are 9 total possible positions for the image:

left top - top left corner of the element's box.
center top - top center of the element's box.
right top - top right corner of the element's box.
left center - left column, center row.
center center - the center of the element's box.
right center - right column, center row.
left bottom - bottom left corner of the element's box.
center bottom - bottom center of the element's box.
right bottom - bottom right corner of the element's box.
Note that the values are in pairs.

p {
  background-image: url("#");
  background-repeat: no-repeat;
  background-position: right top;
}
In the example above, the background image is not repeated. It's positioned in the top right corner of the element's box.

Note: When setting this property, if only one value is specified, the second value will default to center.

Instructions:
1.
In style.css, set the background position of the image in #cover to center bottom.