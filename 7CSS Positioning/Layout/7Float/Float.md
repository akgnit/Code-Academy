So far, you've learned how to specify the exact position of an element using offset properties. If you're simply interested in moving an element as far left or as far right as possible on the page, you can use the float property.

The float property can be set to one of two values:

left - this value will move, or float, elements as far left as possible.
right - this value will move elements as far right as possible.
div.block {
  width: 100px;
  float: left;
}
When an element is floated, any other content within the same containing element will naturally flow around the element.

Floated elements must have a width specified, as in the example above. Otherwise, the element will assume the full width of its containing element, and attempting to float the element may not yield any visible results.

Instructions

1.
Set the float property of the div.answer element to left.