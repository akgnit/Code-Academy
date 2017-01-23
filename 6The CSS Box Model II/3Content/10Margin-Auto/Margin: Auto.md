The margin property also lets you center content, if you follow certain requirements. Take a look at the following example.

div.headline {
  margin: auto;
}
When the margin property is set to auto, the element being styled will center in the page.

In theory, the div in the example above should center on the page, but it doesn't. Why?

In order to center an element, a width must be set for that element. Otherwise, the width of the div will be automatically set to the full width of its containing element, like the <body>, for example. It's not possible, therefore, to center an element that takes up the full width of the page.

div.headline {
  width: 400px;
  margin: auto;
}
In the example above, the width of the div is set to 400 pixels, which is less than the width of the page's body. This will cause the div to center properly on the page.

Note: When margin: auto is used, an element will center relative to its container. For example, the div in the example above was centered relative to the width of the body. If the div was contained in larger div, the smaller div would center relative to the width of the larger div. This is important to keep in mind when attempting to center nested elements, like divs.

Instructions

1.
In style.css, set the margin of #banner-content so that the element centers.

Note that the #banner-content selector already includes a width for the div (60%), less than the full width of its containing element (the banner div in this case).
