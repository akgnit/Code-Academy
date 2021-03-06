The current revision of CSS, CSS3 (at the time of this writing), introduces a new way to specify colors using HSL colors.

HSL stands for Hue, Saturation, and Lightness. Specifically, this is what each means:

Hue - the technical term that describes what we understand as "color." In HSL, hue is represented on a color wheel. It can take on values between 0 and 360.
Saturation - the amount of gray in a given color. In HSL, saturation is specified using a percentage between 0% and 100%. The percentage 0% represents a shade of gray, whereas 100% represents full saturation.
Lightness - the amount of white in a given color. Similar to saturation, lightness is specified using a percentage between 0% and 100%. The percentage 0% represents black, whereas 100% represents white. 50% is normal.
You can use HSL colors in your CSS like this:

h1 {
  color: hsl(182, 20%, 50%);
}
Notice that using HSL is very similar to using RGB.

Note: Because HSL is a part of CSS3, older browsers may not support it. In a later exercise, you'll learn how to work around support issues for colors.

Instructions

1.In style.css, change the color of the main heading and set it to an HSL color with the values 350, 58.8%, 42.0%
