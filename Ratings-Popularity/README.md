# Changelog for Ratings-Popularity Page

This is to help us keep track of what I've done as I proceed.

## [1.0.0] Apr. 7-8, 2025
### Added
- Branch & branch Subfolder
- Initial, very basic, setup 
- Images subfolder
- Logo.jpg
- This README.md file

## [1.0.1] Apr. 11-12, 2025
### Added
- Fixed the issue brought up by @Sam. This was a padding issue in the body. By targeting 
    the body and directly setting its height, margin, and padding to 100vh, 0, 0, the header/nav/and footer max-width of 100% now stretches these sections across the page.
- Added a div section (class=“inner-nav”), made it a grid, to center the links while
    keeping the red bar across the page.
- Targeted the headerlogo so it’s not so large and reduced a bit of the excess padding
    around it.
- Added the Fenice ITC font to the links (more on this font later).
- Increased the font size so the links stand out.
- Changed the hover transition from underline to an expanding highlighted box with red
font (this is the CSS transition).
- Made the header & nav “sticky” (i.e., persistent) so page content scrolls up beneath it.
    If no one likes it, it can be set back to scroll with content.
- Made the footer a bit larger and, hopefully, positioned flush at the bottom of the page
    (let me know if this didn’t work for anyone).
- Added two green note lines to the styles.css sheet so all you have to do is copy the 
    code into your styles sheet and add your specific page content (css) in between the lines. This should hopefully make it easier for everyone.
- Added an @media query so the header and nav are responsive at smaller resolutions –
    they’re set to adjust at 480px and less, capping the nav links and logo at 80px so they’re still readable.

## [1.0.2] Apr. 12-13, 2025
### Added
- A main card for main content (image + updated text)
- 3 side cards for specific ratings info
- Animations so 2 side cards fade into the 3rd and back automatically
- Hover transitions to side card links, similar to that in nav