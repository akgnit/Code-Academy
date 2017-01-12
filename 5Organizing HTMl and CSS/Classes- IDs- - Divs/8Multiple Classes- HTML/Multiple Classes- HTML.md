It's also possible to label HTML elements with more than one class. How is this functionality useful?

You learned that elements that share a styling (e.g. typeface) are labeled with the same class. When those same elements must also be differentiated, however, labeling with an additional class is helpful.

<h1 class="book domestic">The Way of the Deep</h1>

<h1 class="book foreign">A Night in the Sky</h1>
.book {
  font-family: Georgia, serif;
}

.domestic {
  font-color: #0902CC;
}

.foreign {
  font-color: #B097DD;
}
In the example above, the HTML code uses main headings for two different book titles. In this example, all book titles must share the same typeface, so the headings are labeled with a class of book and are then styled with a typeface of Georgia.

The books, however, must be differentiated based on their country of origin. To differentiate the book titles based on this information, two additional classes, domestic and foreign, are applied to the respective headings, which style the color of the heading in the CSS code.

To label an HTML element with an additional class, simply include the class within the double quotes, immediately after the first class. HTML elements can be labeled with many classes, but whenever possible, it's best to limit an element to four classes at most.

Instructions:

In this web page, no HTMl element needs to have multiple classes. However, be aware that using multiple classes for an element is extremely common in web development. Keeping this exercise as reference will come in handy later.
