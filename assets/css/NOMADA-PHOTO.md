
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
- The Landing Page and Destination pages only differ in gallery containers and hover effects used with those gallery containers.
- The Destination Pages differ only in text descriptions and images. The HTML/CSS is the same on each page besides the different image files and text.

## Code

All pages:

- HTML boilerplate for all pages to start, styled using CSS flexbox. All pages have the same Head, Header and Footer.

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
    - Main: The section is divided into two parts: a text area and an image area.
        1. About Body Container
            - The entire section is contained within a section container element with class name "about-body-container", with a maximum width of 1200 pixels, centered horizontally on the page with margins set to 0, and aligned vertically with the center of the page using flexbox properties.
        2. About Textbox
            - The text area is divided into a h3 heading with class name "about-heading" and a div body of text with class name "about-textbox". The heading is styled with a large, bold font and a primary text color. The body of text is styled with a smaller font and a secondary text color.
        3. About Image Grid
            - The image area is divided into two rows: a row of smaller images with class name "about-small-images" and a single larger image with class name "bottom-image" beneath them.
            - The smaller images are arranged in a row with a gap of 10 pixels between them and are each no wider than a certain width, with each image contained within an img tag with class name "about-small-images img". The larger image is twice the width of the smaller images and has a maximum height of 200 pixels, contained within an img tag with class name "bottom-image img".

Contact Page description of Code and Content:

    - Head: Same content as the Gallery Landing and Destination Pages.
       - Body: Header and Footer are the same as the Gallery Landing and Destination Pages.
         - Main
             1. Contact Form Container
                - The form is contained within a forum element with the class "contact-form-container", which is styled to be centered, have a width of 50%, and a border of 20px with a color defined by the variable "--secondary-color". The form itself is within a div with the class "contact-form", which has a background color defined by the variable "--background-color", a maximum width of 40%, and padding of 2em. The form title, defined by an h5 element with the class "contact-title", is styled to have a font family of "--primary-font", be bold and have a font size of 34px.
             2. Contact Form Image 
                - An image is also included in the form, within a div with the class "contact-form-image". The image is centered and has a maximum width of 50%.
             3. Contact Forum
                - This form is a dummy forum setup with GET and an action that will redirect the user back to contact.html essentially reloading the page. The Name, Email and Message text input fields are all required to be completed before the form can be submitted.
                - Text inputs within the form, defined by elements with the class "text-input-contact", have a font family of "--primary-font", regular font weight, font size of 16px, and a color defined by the variable "--text-color-secondary". The input fields have a width of 100%, height of 25px, and a margin of 5px 0 20px 0. They also have a border of 3px with a color defined by the variable "--text-color-secondary" and a border radius of 3px.
                - The message input field, defined by an element with the class "message", has the same styling as the text input fields, but with a height of 150px.
                - When the input fields are in focus, they have an outline removed and a border color of "--accent-color".
                - The submit button has the class "submit-button" and has a width of 100%, box-sizing of border-box, margin-top of 2%, border radius of 2px, and padding of 1em. Its font size is set to 100%, and it has a background color defined by the variable "--accent-color" and text color defined by the variable "--main-color". The button is displayed as a block element. The submit button also has a hover effect that changes it's color.

Media Queries:

## Design and Layout

- Primary Design System is as follows:

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

High Fidelity Wireframes and a Prototype that have been created in Adobe XD can be found here:

- Developer Prototype: <https://xd.adobe.com/view/4d002e9a-15fe-4078-863d-420e3ac33da3-1853/>
- Design Review Prototype: <https://xd.adobe.com/view/4d002e9a-15fe-4078-863d-420e3ac33da3-1853/>
