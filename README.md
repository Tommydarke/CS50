# Project 0

Tom Baker

Web Programming with Python and JavaScript

Assessment criteria:
>Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
--> The 4 pages on this site are the homepage (index.html), "About" (about.html), "Projects" (projects.html) and "epic walks" (walks.html)
--> The navbar displays on every page and allows the user to link to any page from any other. As this navbar is the same on each page an improvement would be to use a PhP include to add the html to each page from a single file or an HTML/javascript include. This would allow changes to the navbar to propagate to each page while only having to change one file
>Your website must include at least one list (ordered or unordered), at least one table, and at least one image.
--> The navbar uses an unordered list styled to display horizontally
--> There is a table on the homepage, also styled with CSS
--> There are various images on the site
>Your website must have at least one stylesheet file.
--> The stylesheet "styles.css" is compiled from an SCSS file
>Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
--> More than 5 CSS properties can be found in "styles.css" inluding width, padding, max-width, color and border
--> The #id selector and .class selector are used in "styles.css" to style the table and homepage image
>Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
--> Using a @media query the homepage image will fit the whole width of a small (eg mobile) screen, on larger screens the image has a max-wdith of 700px, beyond this the image starts to pixellate
>You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
--> Bootstrap is delivered via a CDN
--> The Bootstrap components "Jumbotron" (homepage) and "Navbar" (all pages) are used 
--> On the homepage 3 columns are deployed and will rearrange from horizontal to vertical display as the screen size reduces
>Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.
--> A variable is used in "styles.scss" to set the font-color for emphasis, on the homepage this sets the column header font to blue
--> Nesting and inheritance can be seen in "styles.scss". Nesting is used to style the table on the homepage, inheritance is used to style the headings on the subsequent pages.

>In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.

The files are:
> index.html, about.html, projects.html, walks. html
--> These are the 4 html pages
> styles.scss 
--> This is the main style file. I used "sass --watch styles.scss:styles.css" to automatically compile the .css file
> README.md
--> This file details how the assessment criteria have been met
