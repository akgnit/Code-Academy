In the last unit, you learned how to organize HTML code with IDs, classes, and divs. All of these concepts are necessary to understand advanced CSS styling techniques. An understanding of CSS is not complete, however, without a study of the box model.

In some of the past exercises, you've unknowingly seen aspects of the box model. For example, when you set the background color of an element, you may have noticed that the background color was applied not only to the area directly behind the element, but also to the area to the right of the element. In another exercise, you learned how to align the text. How did the browser know how to align the text?

All HTML elements live within a box. Elements on a web page are understood by the browser as "living" inside of a container, or a box. This is what is meant by the box model.

When you changed the background color of an element, you changed the background color of its entire box. When you aligned text, the text was aligned relative to the element's entire box. To truly create custom websites, you'll have to understand the box model.

In this unit, you'll learn about the following aspects of the box model:

The dimensions of an element's box
The borders of an element's box
The content within an element's box
The area around all four sides of an element's box
Let's begin!

Instruction:

Where are the boxes that supposedly contain all HTML elements? They're invisible, so we'll have to reveal them!

In style.css, add the following code:

* { 
  border: 1px solid rgba(0, 0, 0, 0.3);
}
The code above selects all elements on the page (using the universal selector you learned about earlier) and reveals the borders of their box. Surprise!

Don't worry about the details of the border property. You'll learn about it in this unit.
