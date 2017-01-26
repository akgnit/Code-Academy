A wide variety of different background styles are used across many modern websites today. Some sites use large images in their layout, while others use creative color gradients as their background.

The background-image property you learned about earlier allows you to do more than simply set the background image of an element. It also lets you use color gradients in your web page.

Gradients are planned to be a part of the newest revision of CSS, CSS3. Due to the many browsers available, there is no standard way of defining a gradient using CSS (different browsers require different syntax). In this exercise, we'll look at one value supported on a couple of major browsers.

The background-image property can be set to the following value:

-webkit-linear-gradient() - this value accepts two arguments: the two colors the linear gradient will transition to and from. The colors are usually specified as hex color codes.
div.header {
  height: 400px;
  width: 400px;
  background-image: -webkit-linear-gradient(#666CCC, #BC1324);
}
In a later course, you'll learn more about the -webkit-linear-gradient syntax, as well as other similar CSS values. For now, it's important to understand how to create a linear gradient using the value in the example above.

Instructions

1.
In style.css, add the background-image property to the .btn selector.

Set it equal to a linear gradient, as shown in the example above. The gradient should start at #FFD194 and ends at #BC1324.
