With the background-attachment property, you can specify whether or not a background image should remain at one position on the web page or whether it should move up and down as the user scrolls through a web page.

The background-attachment property can take one of two values:

scroll - this value allows the image to move up and down as a user scrolls on the web page (this is the default value).
fixed - this value pins the image's position on the page.
p {
  background: url("#") no-repeat right center;
  background-attachment: fixed;
}
In the example above, the background image will remained fixed as a user scrolls through the web page.

Instruction:

1.
In style.css, pin the background image in the #cover selector using fixed.

Scroll through the web page and notice the behavior of the background image.