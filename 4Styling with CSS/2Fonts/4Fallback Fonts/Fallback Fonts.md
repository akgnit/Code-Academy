Earlier, you learned that users must have the fonts specified in the stylesheet installed on their computer in order for their browser to display that font. What happens when a font is not installed on a user's computer?

Most computers have a small set of typefaces pre-installed. This small set includes serif fonts and sans-serif fonts, like Times New Roman and Arial, respectively.

When the stylesheet specifies a font not installed on a user's computer, the pre-installed fonts can be used as fallback fonts for users.

To use fallback fonts, the following syntax is required:

h1 {
  font-family: Garamond, Times, serif;
}
The CSS rule above says: "Use the Garamond font for all <h1> elements on the web page. If that font is not available, use the Times font. If both of those fonts are not available, use any serif font pre-installed on the user's computer." The fonts specified after Garamond are the fallback fonts.

Fallback fonts help ensure a consistent experience for the diverse audience of users that visit a site.

Instructions

1. In style.css, add Garamond as the first fallback font for the main heading and subheading, and add serif as the final fallback font.
Stuck? Get a hint

2. Next, set the first fallback font of the paragraph to Arial, and set the final fallback font to sans-serif.
