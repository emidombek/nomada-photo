
# Nomada Photography Readme

## Purpose and goals of the website

To showcase the travel photography work of Nomada photography. This could include photographs from different parts of the world, each highlighting the culture, landscape, and people of that area.

## User stories

- As a potential client, I want to view a portfolio of Nomada photography's work to see if their style aligns with my needs for an upcoming travel project.
- As a photography enthusiast, I want to explore different galleries on the website to see how Nomada photography captures unique travel experiences and to learn more about their techniques and approach to travel photography.
- As a frequent traveler, I want to browse the website to find inspiration for my own travel photography, and to discover new and interesting places to visit based on the images presented.

## Content and Structure

- HTML and CSS Flexbox as well as CSS variable roots
- Github Repo: <https://github.com/emidombek/nomada-photo>
- Page structure:
  - Gallery Landing Page, Destination Pages (8) About and Contact in total there are 11 pages.
  - Overall styling: Removing default margins/padding/borders, adding basic backround color,text styles and display properties to the Body through selecting Body/Header/Main/Footer.
  - Custom styling on some elements, several hover effects have been used in the Header, Main and Footer section of the Body many of these have been removed or modified for smaller screens via media queries.

## Code

All pages:

- HTML boilerplate for all pages to start, styled using CSS flexbox. All pages have the same Head, Header and Footer.
- The Landing Page and Destination pages only differ in gallery containers and hover effects used with those gallery containers.
- The Destination Pages differ only in text descriptions and images. The styling is the same on each page.

- Primary Design system is as follows:

 --font-family: Raleway, sans-serif, Source Serif Pro, sans-serif;
  --primary-font: Raleway, sans-serif;
  --secondary-font: Source Serif Pro, sans-serif;
  --main-color: white;
  --background-color: white;
  --primary-color: #D8D5BF;
  --secondary-color: #AEC1BA;
  --accent-color: #CF755A;
  --text-color-primary: #000000;
  --text-color-secondary: #464646;
  --text-color-accent: #CF755A;
  --text-color-secondary-accent: #737373;
  --line-height: 1.5;

Gallery Landing and Destination Pages description of Code and Content:

(Landing page: index.html) (Destination pages: chelmno.html, connemara.html, tatra.html, torun.html, richmond.html, bydgoszcz.html, slieveleague.html, gdansk.html)

- Head

  1. Contains Metadata for website.
  2. Contains website title.

- Body

  - Header

  1. Hero Image
         - Unusally large hero image which allows the user to experience the photo in fullscreen with hover elements then give context and allow the user to jump further down to the menu section. This has been modified for smaller screens to ensure good UX.
         - The .hero-image class centers and sizes the image container, while the .hero-image img class sets the properties of the image itself.
         - The .image-overlay class creates a darkened overlay effect that can be used with both hero images.
         - The .text-overlay class styles text contained within the image overlay, and the .middle class adds a link that allows users to jump to the menu section of the page.
         - The .text-box-hover class creates a box-like appearance when the user hovers over it.
  2. Logo Banner
        - Large banner below the Hero Image which contains the navigation menu and logo text.
        - The logo banner section has a background color, padding, and is arranged as a flex container with the logo and another element aligned to the left and right sides respectively.
        - The logo itself is styled with a bold font and a specific size, color, and padding. There is also another element styled with a different font size, color, and alignment.
        - The menu section is also a flex container and has its font size and letter spacing set. Each menu item is styled without bullets and with some margin between them.
        - The menu items are links with their own styling, including a hover effect and the option to set one as active. There is also a dropdown menu, which is hidden by default but is shown when a user interacts with it.
        - The #logo element has been left as an id instead of class so it can be reference in links in the .hero-image-container section as well and the Footer .footer-text-container.
        - The menu section is also a flex container and has its font size and letter spacing set. Each menu item is styled without bullets and with some margin between them. The menu items are links with their own styling, including a hover effect and the option to set one as active.
        - There is also a dropdown menu, which is hidden by default but is shown when a user interacts with it via hover effect. This dropdown has been excluded from mobile devices.

  - Main

   1. Gallery
        - The gallery container uses grid display to organize its images in columns and rows, with specific column width, row height, column gap, and row gap. This container is used to display the 8 images with corresponding links that lead the user to the destination pages.
        - The gallery-container2 has a different row height setting that repeats twice and ensures an equal amount of space in the container is occupied by the rows. This container is used to display the 4 images on the destination pages.
        - The h4 element is set to display none, which means it won't be visible in the gallery.
        - The images in the gallery columns are set to object-fit: cover, which means they will scale and crop to fill the available space while maintaining their aspect ratio, and object-position: top is used to align the images at the top of the container.
        - The image-overlay and image-overlay2 classes are used to create an overlay on the images, with a semi-transparent black background and centered text.
        - The gallery-column i and gallery-column-center i classes define an icon for the gallery columns, which is set to the main color.
        - Finally, the text-overlay2 class is used to create a text overlay on top of the images, positioned at the center of the container.

  - Footer

    1. Footer Banner
        - The Footer Banner is a larger banner that contains social media icons that link to different social media sites. There is also a heading that links to the #logo at the top of the page which takes the user back to the menu when selected.
        - The footer container (footer-text-container) is positioned absolutely and arranged as a vertical column. It has a background color and text color specified.
        - The main footer text (footer-text) has a background color, bold font, and centered alignment. It transitions smoothly when its color changes via hover effect.
        - The copyright text (copyright-text) has a specific color, font, and alignment.
        - Social network icons (social-networks) are displayed as a horizontal list in the center. Each icon has some margin around it.
        - The social network icon elements (social-networks i) have a larger font size, centered alignment, and a specific color. They also transition smoothly when their color changes via hover effect.

About Page description of Code and Content:

- Head: Same content as the Gallery Landing and Destination Pages.
  - Body: Header and Footer are the same as the Gallery Landing and Destination Pages.
    - Main
        1.

## Design and Layout

High Fidelity Wireframes and a Prototype that have been created in Adobe XD can be found here:

- Developer Prototype: <https://xd.adobe.com/view/4d002e9a-15fe-4078-863d-420e3ac33da3-1853/>
- Design Review Prototype: <https://xd.adobe.com/view/4d002e9a-15fe-4078-863d-420e3ac33da3-1853/>

Header element:

- Hero image on each page, banner color #D8D5BF containing Logo and Menu with hover bottom border, menu text is Raleway 16px semibold with 2px hover border in #CF755A.
- Logo is 40px Bold Raleway in #CF755A and 16px Raleway in Semibold using #464646.

Gallery Landing Page Main Body:

- Body for Gallery Landing page to have white background color and 2 columns of 4 images each, within a div container.
- Hover element that grays over image with 70 percent transparency + icon.
- Clickable images on the landing page will lead to destination pages that include a further 4 images from each destination along with a description via hover element.

About Main Body:

- H1 header for About section on About page, Left side section or div with p child element containing about description. Font is Source Serif Pro in 16px.
