RGB colors, hex color codes, and HSL colors offer web developers an extraordinary amount of color customization options. As these properties become more advanced, however, it's important to keep in mind that not all users browse the Internet with the same browser, let alone the same version of a given browser.

How does this affect web development? Newer revisions of HTML and CSS affect older browsers. Older browsers, over time, will become dated (possibly obsolete) and not be able to support newer CSS features. For example, many older browsers do not support RGBa, HSL, or HSLa.

Because of this, we must include redundant color options in our CSS code that can cater to a wide audience of different browsers.

Specifically, we can add multiple CSS color declarations, just in case a user's browser can't support a certain declaration.

h1 {
  color: rgb(22, 34, 88);
  color: rgba(22, 34, 88, 0.4);
}
In CSS, the latter of multiple declarations takes priority. In the example above, if the user's browser supports rgba(), then that color will be applied to the heading. If it does not, then CSS will use the first rgb() color declaration, as a backup.

Using redundant declarations allow you to support as many users as possible across multiple versions of different Internet browsers.

Instructions

1. In style.css, set the color of the main heading to an RGB color with the values 3, 150, 100.

2. On the next line, set the main heading's color to an RGBa color with the values 3, 101, 100, 0.75.

Which color was applied to the heading?
