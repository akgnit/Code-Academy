IDs are great for labeling unique elements, but IDs have a limitation. Because unique IDs should not be used across multiple HTML elements, they are insufficient for quickly styling elements that should all share a specific style.

CSS offers a solution to this limitation. For multiple elements that should share the same styling, classes can be used to label them.

To label an element with a class, we can use the class attribute on an HTML element.

<h1 class="science">Scientist Discovers Important Cure</h1>

<h1 class="science">New Study Reveals The Importance of Sleep</h1>
In the example above, there are two headings with a class of science. Why?

HTML elements are often labeled with class names that reflect the content they represent on the web page. In the example above, perhaps a news company decided that all news headlines about science should be labeled with a class of science.

Later, in the stylesheet, all science headlines can be quickly styled to have the same styling.

Instructions

1. In index.html, give the second <div> a class of partner.
