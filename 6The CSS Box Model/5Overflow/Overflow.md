When the value of the max-height property is set too low, the contents will spill outside of the box. How can we ensure that this doesn't happen?

The overflow property controls what happens to content when it spills, or overflows, outside of its box. It can be set to one of the following values:

hidden - when set to this value, any content that overflows be hidden from view.
scroll - when set to this value, a scrollbar will be added to the element's box so that the rest of the content can be viewed by scrolling.
p {
  min-width: 300px;
  max-width: 600px;
  min-height: 150px;
  max-height: 300px;
  overflow: scroll; 
}
In the example above, minimum and maximum widths and heights have been set. If any of the paragraph content overflows (perhaps a user resizes their browser window), a scrollbar will appear so that users can view the rest of the content.

Instructions

1.
In style.css, add the overflow property to the content-box class selector and set it to scroll any content that overflows.

Take a look at the web page to the right. Notice how the content in the middle scrolls now.
