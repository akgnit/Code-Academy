In an earlier unit, we showed you how all HTML elements have boxes around them. Images are no exception. Because images are also contained within boxes, they can also be modified using some of the properties that we used earlier to modify boxes.

For example, we can modify the dimensions of an image using the width and height properties.

<img src="#" alt="" class="" />
img.X {
  width: 350px;
  height: 200px; 
}
It's important to specify the width and height for an image on your web page, as this helps the browser know exactly how much space should be reserved for the image, rather than having to download an entire image for the user.

Ideally, however, images should be saved at the dimensions that they will be displayed. For example, rather than specify a height and a width for an image using CSS, that....

Instructions

1.
Take a look at the images of bicycles on the page. At the moment, they're too big, so let's modify their dimensions.

In style.css, in the .product img selector, set the width 100%.

Note: .product img refers to all images within elements that have a class name of product.