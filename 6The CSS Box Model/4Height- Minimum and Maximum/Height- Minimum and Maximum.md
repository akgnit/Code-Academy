You can also limit the minimum and maximum height of an element.

min-height - this property ensures a minimum height for an element's box.
max-height - this property ensures a maximum height for an element's box.
p {
  min-height: 150px;
  max-height: 300px;
}
In the example above, the height of all paragraphs will not shrink below 150 pixels and the height will not exceed 300 pixels.

What will happen to the contents of an element's box if the max-height property is set too low? It's possible for the content to spill outside of the box, resulting in content that is not legible. You'll learn how to work around this issue in the next exercise.

Instructions:
1.
In style.css, set the minimum height of the paragraph to 100 pixels.

After you've done this successfully, resize the browser and notice how the height of paragraph's box will no longer shrink below 100 pixels.
2.
In style.css, set the maximum height of the paragraph to 200 pixels.

After you've done this successfully, resize the browser and notice how the height of paragraph's box will no longer expand beyond 200 pixels.
