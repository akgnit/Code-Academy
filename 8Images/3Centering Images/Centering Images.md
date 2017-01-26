Images can also be centered, but first, their default behavior must be changed. By default, images are inline elements. For images to center properly, they must behave as block-level elements.

img.leaf {
  width: 300px;
  height: 200px; 
  display: block;
}
In the example above, the image's display property has been set to block. Now the image can be aligned as a block-level element.

img.leaf {
  width: 300px;
  height: 200px; 
  display: block;
  margin: 0px auto;
}

In the example above, the image is aligned using the margin property. The top and bottom margins of the image's box are set to 0 margin. The left and right margins are set to auto, which automatically sets the exact amount of margin needed on the left and right sides in order to center the image.

Note: To align images to the left or right side of a page, you can use the float property you learned about earlier.