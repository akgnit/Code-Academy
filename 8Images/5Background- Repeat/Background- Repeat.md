In the last exercise, you probably noticed that the background image was repeated, creating a tiled background (this is the default behavior).

You can control how a background image repeats with the background-repeat property. This property can take one of four values:

repeat - the default value — the image will repeat horizontally and vertically.
repeat-x - the background image will be repeated only along the x-axis (horizontally).
repeat-y - the background image will be repeated only along the y-axis (vertically).
no-repeat - the background image will not be repeated at all and will appear only once.
p {
  background-image: url("#");
  background-repeat: repeat-x;
}
In the example above, the paragraph's background image will repeat horizontally.

Instructions:

1.
In style.css, make sure that the background image of #cover element does not repeat.
