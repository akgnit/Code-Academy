The float property can also be used to float multiple elements at once. When multiple floated elements have different heights, however, this can affect their layout on the page. Specifically, elements can "bump" into each other and not allow other elements to properly move the left or or the right.

Setting the clear property of an element lets you specify how elements should behave when they bump into each other on the page.

The clear property specifies how elements should behave when they bump into each other on the page. It can take on one of the following values:

left - the left side of the element will not touch any other element within the same containing element.
right - the right side of the element will nottouch any other element within the same containing element.
both - neither side of the element will touch any other element within the same containing element.
none - the element can touch either side.
div {
  width: 200px;
  float: left;
}

div.special {
  clear: left;
}
In the example above, all divs on the page are floated to the left side. The div with class special did not move all the way to the left because a taller div blocked its positioning. By setting its clear property to left, the special div will be moved all the way to the left side of the page.

Instructions:

1.
Take a look at the .answers divs on the web page. They have been floated to the left, but the .question divs are touching the .answer divs on the right, let's fix this.

In the .question selector, set the clear property to left. Notice how the questions moved.
2.
On second thought, this layout is not looking so good. Remove the float property from .answer and the clear property from .question.