Now that you know how to organize code into sections using divs, we can start labeling divs with classes instead, rather than labeling individual elements with classes.

This does not mean that labeling individual elements with classes is no longer useful. Even when divs are labeled with classes, there will be many other times when an individual element will need to be labeled with a class.

<div class="container">
  <h1 class="title">Alice In Wonderland</h1>
  <p> ... </p>
</div>
div.container {
  background-color: rgb(252, 255, 205);
  font-family: Roboto, Helvetica, sans-serif;
}

h1.title {
  color: #0D1A2F;
}
In the example above, a heading and paragraph are contained within a div that has a class of container. In the stylesheet, the background color and typeface of the div have been styled.

Divs are intended to contain other HTML elements, not raw text. Does it make sense to style a div directly then?

When a div is styled, all elements inside of the div will inherit the styling applied to the div. This example illustrates how easy it is to style sections of a web page using div.

Note: The example above uses a class called container. Chances are that you'll frequently see this class name as you learn more about web development.


Instruction:

1.
Give the div that you added in the last exercise a class of prop.
2.
Notice that there are three divs in index.html with a class of prop. Let's organize these three divs into a larger, containing div.

Enclose these three divs with a div that has a class called value-props.
3.
Finally, let's contain the value-props div into an even larger div.

Enclose the entire value-props div with a div that has a class of main.

Note: Be sure to also enclose the <h3> and <p> elements above the value-props div.
