New fonts are constantly being developed. Because there are so many new fonts available, it would be unrealistic to expect users to have all of them installed on their computers.

Fortunately, you don't have to predict which fonts are installed on a user's computer. Many (but not all) of the new fonts that emerge on a daily basis are being centralized in directories made available for public use.

For example, Google offers Google Fonts, a directory of thousands of open-source fonts that are free to use by anyone.

To use these fonts, you can link to a specific Google Font in your HTML code and use it immediately in your stylesheet. Because the HTML file links directly to the Google Font, a user's browser can display the typeface you specify. This avoids having to determine whether or not that font is installed on a user's computer.

To use a Google Font, you can use a <link> element, just like you did for a CSS stylesheet:

<head>
  <link href="https://fonts.googleapis.com/css?family=Raleway" type="text/css" rel="stylesheet" >
</head>

In the example above, the href attribute is set to the following URL, which was retrieved from Google Fonts:

https://fonts.googleapis.com/css?family=Raleway
The URL in the example above specifies the Raleway typeface from Google Fonts.

You can use the new font just as you would use any other font:

h1 {
  font-family: Raleway, Georgia, serif;
}
You now have access to thousands of new, modern, free-to-use fonts!

1. In index.html, add a link to the Google Font Roboto. Use the following URL:

https://fonts.googleapis.com/css?family=Roboto:100
The 100 in the URL specifies an optional font weight for Roboto (don't worry, you'll learn about font weight in this lesson).

2. In style.css, specify Roboto as the font family for the subheading and the paragraph, followed by sans-serif as the fallback font

Notice how the fonts changed!

3. In index.html, add an additional link to the Google Font Playfair Display. Use the following URL:

https://fonts.googleapis.com/css?family=Playfair+Display

4. In style.css, specify Playfair Display as the font family for the main heading, followed by serif as the fallback font.
