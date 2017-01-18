What if you don't want all four sides of a box's content to have equal padding?

In that case, another version of the padding property lets you specify exactly how much padding there should be on each side of the content.

p {
  border: 3px solid #XXXXXX;
  padding: 5px 10px 5px 10px;
}
In the example above, the four values 5px 10px 5px 10px refer to the amount of padding in a clockwise rotation. In order, it specifies the amount of padding on the top (5 pixels), right (10 pixels), bottom (5 pixels), and left (10 pixels)sides of the content.

When this version of the padding property is used, a padding value must be specified for all four sides of the content.

Instructions
1.
In style.css, set the padding on the top and bottom of the #banner-content selector paragraphs to 30 pixels, and set the padding on the left and right to 10 pixels.
