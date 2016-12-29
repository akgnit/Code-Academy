You learned that RGB and hex color codes are two different methods of representing the same thing: color. However, there is one feature that RGB colors support that hex color codes do not: opacity.

Opacity is a measure of how transparent a color is. To modify opacity in RGB colors, CSS offers the rgba() value. Note the slight difference in rgb() and rgba().

The extra a character in the rgba() value is known as the alpha value. It represents the opacity of a color. The alpha value can be a number between 0 or 1, inclusive.

h1 {
  color: rgba(123, 88, 9, 0.5);
}
In the example above, the alpha value has been set to 0.5. This indicates that the color of the heading will be set to 50% of its normal opacity.

Note: The alpha value can also be used for HSL colors, using hsla():

h1 {
  color: hsla(239, 45%, 22%, 0.4);
}
1.
In style.css, change the color of the main heading and set it to an RGBa color with the values 2, 93, 140 and an opacity of 0.6.
2.
Notice how the main heading is now transparent. Let's make it more opaque to make it easier to read for users. Keep the same color, but change the alpha value to 0.9.
