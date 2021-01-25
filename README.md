This is a tweaked version of the "Just the Docs" theme for Github Pages.

I make the following changes to customize it for my own use:

- css changes
    - stylesheet is now static .css instead of sass
    - color scheme is handled via css variables, and changed to a solarized-style color scheme.
    - deleted a bunch of the JTD utility classes that I don't need.
    - changed font properties so diacritics are rendered properly
    - added styling so that `<aside>` elements are placed in the page margins
    - removed some annoying css overengineering:
        - Unordered lists just use the default rendering instead of the convoluted JTD thing where the bullet points are removed then replaced.
        - links (`<a>` elements) don't have wordwrap turned off.
- Removed the footer
- added latex rendering with katex 
- toggled off html compression
