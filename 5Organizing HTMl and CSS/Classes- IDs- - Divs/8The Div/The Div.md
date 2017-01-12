Classes and IDs are useful for labeling elements, but a disorganized, overuse of classes and IDs can result in an HTML file that is difficult to read. We need a way of organizing the contents of the HTML file. This will help:

Keep HTML code easy to read.
Group elements that belong together.
HTML offers an element that is the backbone of code organization: the div, represented by <div> in HTML.

You can think of the div as a box, or container, that groups elements that belong together.

For example, a <div> can be used to group together all of the elements that make up the navigation for a web page, or any other section of a page.

<div>
  <h1>Alice In Wonderland</h1>
  <p> ... </p>
</div>
In the example above, a heading for "Alice In Wonderland" and a brief paragraph description of the book are contained within a single <div>. If more books were to appear on the page, additional divs could be used to organize them. This would keep the code easier to read, maintain, and style.

Instruction:

1.
Scroll down in index.html. You'll notice this bit of code sitting by itself:

<img src="https://s3.amazonaws.com/codecademy-content/courses/web-101/unit-5/htmlcss1-img_diamond.png" width="60px">
<h2>Luxury</h2>
<p>We understand that you expect the world of your vacation - Jetsetter can provide once in a lifetime experiences at top of the line quality.</p>
Enclose this bit of code with a div.
