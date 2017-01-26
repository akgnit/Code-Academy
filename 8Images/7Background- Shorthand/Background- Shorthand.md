In the last few exercises, you learned how to set a background image, its repetition pattern, and its position using three different properties. CSS allows you to set all three properties at once using a shorthand property: background.

Previously, we set these three properties as follows:

p {
  background-image: url("#");
  background-repeat: no-repeat;
  background-position: right center;
}
The code in the example above can be shortened using the background property.

p {
  background: url("#") no-repeat right center;
}
Note that the background property includes all of the properties that we previously styled individually: background image, repetition, and position (in that order). It's considered best practice to follow this order of values when setting the background property.

Instructions:

1.
In style.css, replace the three background image declarations with a single background property that reuses the same values.