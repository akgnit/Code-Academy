Although named colors provide 147 different options, this is a small amount when you consider the flexibility of CSS. To take 
advantage of the full spectrum of colors that CSS supports, you have the option of using RGB colors.

RGB (Red, Green, Blue) colors offer the option of 16,777,216 possible colors. How is that possible?

RGB colors work by mixing together different amounts of red (R), green (G), and blue (B). Each color (R, G, or B) can take 
on 1 of a possible 256 values (between 0 and 255). This results in 16,777,216 possible colors.

To use RGB colors, you can use the rgb() value when styling a color.

h1 {
  color: rgb(123, 20, 233);
  background-color: rgb(99, 21, 127);
}
In the example above, the value of color is set to rgb(). The three numbers in the parentheses represent the values for R, G, 
and B, in that order. Note that you can use rgb() for background colors as well.

How can you tell what color the RGB values in the example above will result in? Are you expected to memorize 16,777,216 
possibilities? Thankfully, no!

There are many resources on the Internet known as "color pickers" that allow you to view the result of different RGB values 
before you decide to use a certain color. If you're ever in need of a color picker resource, a quick Google search will yield 
the results you are looking for.

1. In style.css, remove the named color for the main heading and set it to an RGB color with the following values: 54, 74, 101.

2. Next, remove the named color for the subheading's background and set it to an RGB color with the following values: 23, 108, 224.
