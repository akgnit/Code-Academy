Take a look at the following code. What do you notice about the margin values?

p {
  margin: 6px 12px 6px 12px;
}
The top and bottom values of margin are the same (6px) and the left and right value of margin are also the same (12px).

Just like the padding shortcut, when you're certain that the top and bottom values for margin will equal each other, and that the left and right values for padding will also equal each other, you can use the following shortcut:

p {
  margin: 6px 12px;
}
The first value, 6px, sets a margin value for the top and bottom sides of the box. The second value, 12px sets a margin value for the left and right sides of the box.

Instructions

1.
In style.css, use the margin shortcut to set the margin on the top and bottom of all list items to 0 pixels, and set the margin on the left and right to 20 pixels.
