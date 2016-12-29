There's an additional way to specify colors in CSS: hexadecimal color codes, often referred to as "hex color codes" for short.

Hex color codes also offer 16,777,216 color options, but they follow a different syntax.

When specifying an RGB color mixture, the values are in base 10. Hex color codes, however, use base 16, or hexadecimal base (hence the name), to specify color mixtures.

h1 {
  color: #09AA34;
}
When read from left to right, each group of two characters responds to a value for red, green and blue, respectively. In the example above, 09 refers to the value for red, AA refers to the value for blue, and 34 refers to the value for green. All hex color codes begin with a # character.

Is there a difference between RGB values and hex color codes?

Not really. RGB values and hex color codes are different ways to represent the same thing: color. It's possible to convert back and forth between RGB values and hex color codes (color pickers often help with this conversion).

Note: When a hex color code is composed of entirely of the same characters, the hex color can be abbreviated, like so:

h1 {
  color: #FFFFFF;
  color: #FFF; /* This is the same color as above */
}

h2 {
  color: #AA33BB;
  color: #A3B; /* This is the same color as above */
}

Instructions

1. In style.css, change the color of the main heading to #452F73.

2. Next, change the background color of the subheadings to #AA8EB5.
