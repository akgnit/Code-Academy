Because a web page can be viewed through displays of differing screen size, the content on the web page can suffer from those changes in size. To avoid this problem, CSS offers two properties that can limit how narrow or how wide an element's box can be sized to.

min-width - this property ensures a minimum width for an element's box.
max-width - this property ensures a maximum width for an element's box.
p {
  min-width: 300px;
  max-width: 600px;
}
In the example above, the width of all paragraphs will not shrink below 300 pixels, nor will the width exceed 600 pixels.

Content, like text, can become difficult to read when a browser window is narrowed or expanded. These two properties ensure that content is legible by limiting the minimum and maximum widths of an element.


Instructions:

1.
In style.css, set the minimum width of the paragraph to 200 pixels.

After you've done this successfully, resize the browser and notice how the paragraph's box will no longer shrink below 200 pixels.
2.
Next, set the maximum width of the paragraph to 800 pixels.

After you've done this successfully, resize the browser and notice how the paragraph's box will no longer expand beyond 800 pixels.
