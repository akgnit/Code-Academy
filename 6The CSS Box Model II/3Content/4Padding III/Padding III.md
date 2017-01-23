Take a look at the following code. What do you notice about the padding values?

p {
  padding: 5px 10px 5px 10px;
}
The top and bottom values for padding are the same (5px) and the left and right values for padding are also the same (10px).

When you're certain that the top and bottom values for padding will equal each other, and that the left and right values for padding will also equal each other, you can use the following shortcut:

p {
  padding: 5px 10px;
}
The first value, 5px, sets a padding value for the top and bottom sides of the content. The second value, 10px sets a padding value the left and right sides of the content.

Instructions

1.
In style.css, use the padding shortcut to set the padding on the top and bottom of the #banner-content selector to 30 pixels, and set the padding on the left and right to 10 pixels.
