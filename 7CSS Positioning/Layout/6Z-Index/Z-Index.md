When boxes on a web page have a combination of different positions, the boxes (and therefore, their content) can overlap with each other, making the content difficult to read or consume.

div.navigation {
  background-color: #4BF5FF;
  width: 100%;
  height: 100px;
  position: fixed; 
}

div.description {
  background-color: #1D09AF;
  width: 50px;
  height: 50px;
  position: relative;
  top: 200px;
}
In the example above, the description div would ignore the navigation div and overlap it as a user scrolls. The opaque background color of the navigation div is not enough to prevent this from happening.

The z-index property controls how far "back" or how far "forward" an element should appear on the web page.

The z-index property accepts integer values. Depending on their values, the integers instruct the browser on the order in which elements should be displayed on the web page.

div.navigation {
  background-color: #4BF5FF;
  width: 100%;
  height: 100px;
  position: fixed;
  z-index: 1; 
}

div.description {
  background-color: #1D09AF;
  width: 50px;
  height: 50px;
  position: relative;
  top: 200px;
}
In the example above, the z-index of the navigation div has been set to 1, which instructs the browser to move this div forward and stack it "on top" of the other elements when the user scrolls.

It's not necessary to set the z-index of the description div to 0 or anything lower than 0. Setting the z-index of navigation to a number greater than 0 is sufficient to prevent overlapping content.

Instructions

1.
In style.css, set the Z index of .header to 1000. Notice how the header is no longer overlapping with the "Welcome" div.