An element's box has two dimensions: a height and a width. In HTML, all boxes have default dimensions. These default dimensions are automatically set to hold the raw contents of the box.

To modify the default dimensions an element's box in CSS, you can use the width and height properties.

These two properties can be specified with the following units of measurement:

Pixels - You learned about pixels when you learned about fonts. This unit lets you set the exact size of an element's box.
Ems - This unit sets the dimensions of the box relative to the size of the text within the box.
Percentages - This unit sets the dimensions of the box relative to the size of the box that it is encased in. For example, consider an element (a box) of class blue set to a height of 200 pixels and a width of 200 pixels. Inside of blue, consider another box of class red, set to a height of 37% and a width of 45%. The resulting dimensions of the red box would be a height of 74 pixels and a width of 90 pixels.
Developers often use ems or percentages to set box dimensions. Because many web pages are now accessed on mobile devices and other displays of differing sizes, ems and percentages allow boxes to scale depending on the size of a user's display.

Instructions:

1.
In style.css, set the height of the content-header div to 320 pixels.
2.
Next, set the width of the navigation div to 100%.

Note: The browser to the right is, of course, a smaller version of a typical browser you might use. In order for the web page to look presentable in this smaller viewport, we'll continue to use percentages for box dimensions. In a later course, you'll learn more about responsive web design.

