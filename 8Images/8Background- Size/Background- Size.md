To modify a background image's size, you can use the background-size property.

This exercise will focus on two of the most common values of the background-size property:

cover - expands the image as large as possible to cover the full width or height of a container. If the dimensions of the container (say, a div) are larger than the dimensions of the image, the image will become distorted. This value is best for images that don't communicate important content to the user, like background images.
contain - expands the image as large as possible, but the image will be letterboxed, which means it won't cover the full width or height of a container.
div.header {
  height: 400px;
  width: 100%;
  background: url("#") no-repeat right center;
  background-size: cover;
}
In the example above, the background image will expand to cover the full size of the div.

Instructions

1.
In style.css, set the background size of #cover to contain.

2.
The background image is letterboxed and it doesn't make sense to use contain for a background image in this case. Change the background size of #cover to cover.