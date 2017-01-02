There are three units of measurement for font size:

1. px - Represents the unit of pixels. The display of a computer monitor can be measured in pixels. A pixel is a small point on the display. How small? Most computer monitors have a resolution of 72 pixels per inch, so a pixel represents about 1/72nd of an inch. Pixels are sometimes also referred to as points. Pixels are used to set the exact size of an element, in this case, text.

p {
  font-size: 18px;
}

2. ems - Pronounced just as it looks, "em." An em is equal to the width of the letter "m". Ems are a relative unit of measurement. They change the size of text relative to the parent element's size of text.

p {
  font-size: 1.3em;
}

3. % - Percentages are also a relative unit of measurement. The default size of text in web browsers is 16 pixels, or 16px. When percentages are used, they set the size of text relative to this default size. For example, setting the font size to 200% would be equivalent to setting it to 32px.

p {
  font-size: 150%;
}
