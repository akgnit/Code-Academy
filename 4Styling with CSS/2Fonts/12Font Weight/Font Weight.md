You've probably noticed bolded text across many different web sites. It's common to bold important headings or keywords.

In CSS, the font-weight property turns bold on or off.

p {
  font-weight: bold;
}
In the example above, all paragraphs on the web page would appear bolded.

The font-weight property has a second value: normal. Why does it exist?

If we wanted all text on a web page to appear bolded, we could select all text elements and change their font weight to bold. If a certain section of text was required to appear normal, however, we could set the font weight of that particular element to normal, essentially "shutting off" bold for that element.

In later units, you'll learn how to be more selective about what parts of your site you'd like to style.

Instructions

1.
In style.css, set the font weight of the paragraph to bold. It'll be difficult to notice, but the letters in the paragraphs will thicken a bit.
2.
Earlier, you added the following line of code to index.html:

<link href="https://fonts.googleapis.com/css?family=Roboto:100" rel="stylesheet">
Notice the 100 in the URL. This specifies that you'd like to use a font weight of 100 when linking to the Roboto font. It's possible to specify a different font weight, or even multiple within the same URL.

Font weights can be set to 100 (thin), 200, 300, 400 (normal weight), 500, 600, 700, 800, or 900 (bold).

In style.css, set the font weight of the paragraph to 100.
