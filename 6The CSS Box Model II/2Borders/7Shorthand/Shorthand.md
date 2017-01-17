In the last few exercises, you learned how to set a border's style, width, and color with three different properties. CSS allows you to style all three properties at once with a shorthand property.

The shorthand way of setting border style, width, and color can be achieved with the border property. Let's look at how we can decrease the amount of code bloat with this property.

div.container {
  border-style: solid;
  border-width: 3px;
  border-color: rgb(22, 77, 100);
}
The code in the example above can be shortened using the border property:

div.container {
  border: 3px solid rgb(22, 77, 100);
}
Note that the border property includes all of the properties that we previously styled individually: width, style, and color.

It's considered best practice to follow the width-style-color order when using the border property.

Instructions

1.
In style.css, set the border of the .hotel to 2 pixels wide, a solid line, and the color #FFF.
