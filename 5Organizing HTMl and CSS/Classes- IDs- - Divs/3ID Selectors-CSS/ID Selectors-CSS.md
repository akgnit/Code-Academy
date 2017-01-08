Now that you know how to label HTML elements with an ID, we can style that specific element in the stylesheet.

In a previous lesson, you learned how to target HTML elements with element selectors, like so:

p {
  font-size: 10px;
  font-color: #A091DD;
}
Remember, however, that an element selector like the one in the example above would targets all paragraphs on the web page. In the example above, all paragraphs are styled to have a font size of 10 pixels and a font color of #A091DD.

To style a specific element labeled with an ID, you can use an ID selector in the stylesheet.

#botswana {
  background-color: #56ABFF;
}
In the example above, the HTML element with an ID of botswana is targeted with the ID selector #botswana.

All ID selectors begin with the octothorpe character: #. The value of the ID immediately follows the octothorpe. Once you've correctly targeted the element, you can proceed to style it as usual.

Instructions

1. In style.css, add an ID selector for the ID header-text.
