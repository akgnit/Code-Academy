If you've ever used a formatted word processor, chances are that you probably also used a feature that allowed you change the "type of font" you were typing in. The phrase "type of font" refers to the technical term typeface, or font family.

To change the typeface of text on your web page, you can use the font-family property.

h1 {
  font-family: Garamond;
}
In the example above, the font family for all main heading elements has been set to Garamond.

When setting typefaces on a web page, keep the following points in mind:

The font specified in a stylesheet must be installed on a user's computer in order for that font to display when a user visit the web page. We'll learn how to work around this issue in a later exercise.
You've probably noticed that we haven't been specifying a typeface in previous exercises of this course. How exactly does the browser know what typeface to use when displaying the web page? The default typeface for all HTML elements is Times New Roman. You may be familiar with this typeface if you have ever used a formatted word processor.
It's a good practice to limit the number of typefaces used on a web page to 2 or 3.
When the name of a typeface consists of more than one word, it must be enclosed in double quotes (otherwise it will not be recognized), like so:
h1 {
  font-family: "Courier New";
}
Instructions

1. In style.css, change the font family of the main heading and subheading to Georgia.

2. Next, change the font family of the paragraph to Helvetica.
