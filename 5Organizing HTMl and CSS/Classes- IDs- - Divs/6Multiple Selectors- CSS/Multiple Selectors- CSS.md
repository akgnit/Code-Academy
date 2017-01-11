CSS does not limit you to selectors that target a single element or class.

In a previous exercise, you learned how to use a multiple element selector to style multiple elements at once.

h1, p {
  font-family: Garamond, serif;
}
The same syntax can be used to style multiple classes at once.

.first, .last {
  font-size: 20px;
}
Using a multiple class selector is an efficient way of styling multiple HTML elements.

Instructions:

1. Scroll down in style.css and take a look at the .prop and .partner CSS rules. They both share the same text-align setting. Delete this property from both CSS rules.

Next, create a CSS rule that uses two multiple class selectors at once (.partner, .prop). Inside of the rule, set the text-align property to center.

This is one example of using a selector that targets multiple CSS classes at once.
