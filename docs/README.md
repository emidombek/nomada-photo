# Nomada Photography Readme

![Devices Preview](/docs/images/nomada_photo_preview_screen.png)

Website link: <https://emidombek.github.io/nomada-photo/>

## Purpose and goals of the website

The purpose of the website is to exhibit the captivating travel photography portfolio of Nomada Photography. It aims to showcase a diverse range of photographs capturing landscapes and the people from various locations around the world. The website's primary goal is to engage users by immersing them in the stunning visuals and offering an overview of the photographer's body of work. Additionally, the website provides a convenient way for visitors to contact Nomada Photography through a web form, ensuring easy communication. Social media links are also provided for users to connect with the photographer on various platforms.

## User stories

- As a potential client, I want to view a portfolio of Nomada photography's work to see if their style aligns with my needs for an upcoming travel project.
- As a photography enthusiast, I want to explore different galleries on the website to see how Nomada photography captures unique travel experiences and to learn more about their techniques and approach to travel photography.
- As a frequent traveler, I want to browse the website to find inspiration for my own travel photography, and to discover new and interesting places to visit based on the images presented.
As a potential client, I want to contact the photographer via the website's contact form to inquire about availability, pricing, and discuss specific requirements for my upcoming travel project.
- As an average user, I want to have a user-friendly and visually appealing browsing experience on the website. I expect intuitive navigation and clear organization of the galleries, allowing me to easily explore Nomada photography's work and navigate between different travel destinations.

## Content and Structure

- HTML and CSS Flexbox as well as CSS variable roots
- Github Repo: <https://github.com/emidombek/nomada-photo>
- Page structure:

  - Gallery Landing Page, Destination Pages (8) About,Contact and Thank You in total there are 12 pages:

  1. Gallery Landing Page:

     - The first thing the user sees on a is a large fullscreen hero image that on hover allows the use to click on link that takes them down further to the Logo Banner and Navigation Menu. This is meant to engage and immerse the user in the image and the place the photograph was taken in (this same large hero image and hero link is employed for every webpage on the site):
       ![Main Gallery Landing Page Screenshot](/docs/images/landing_page_screenshot.png)
     - After the user clicks the link the page jumps down to the Logo Banner where the logo of the Photographer is seen as well as a Navigation Menu (the page layout has been modified for mobile devices and other devices that respond to touch). The gallery of the main body is also partially visible this is meant to entice the user to scroll through. There are eight photos in total of different destinations in this gallery that lead to 8 destination pages when the photo is clicked on or tapped, on devices that can hover an icon will appear that can be clicked on non-hover devices the icon will be displayed immediately:
       ![Main Gallery Landing Page Screenshot with icon hover](/docs/images/landing_page_hover_icon_link_screenshot.png)
     - At the bottom of every page is a footer with social media links and a 'Nomada Photography' link that takes the user back to the top of the Logo Banner where the Navigation Menu is. Underneath this is the copyright text:
       ![Footer Banner](/docs/images/landing_page_footer_screenshot.png)

  2. Destination Pages

     - The Destination Pages allow the user to view an additional 4 images from the selected destination. There is a hover/tap to reveal that allows users to view information on where and when the photo was taken:
       ![Footer Banner](..//docs/images/)
     - The Destination Pages differ only in text descriptions and images. The HTML/CSS is the same on each page besides the different image files and text.

  3. About Page

     - The About Page contains a small gallery of selected images and a small about section:
       ![Footer Banner](/docs/images/about_page_screenshot.png)

  4. Contact Page
     - The Contact Page includes a dummy webform:
       ![Footer Banner](/docs/images/contact_page_screenshot.png)

  5. Thank You Page
     - The user is redirected to this page when submitting a message via the Contact Form.

## Design and Layout

The design for the website was created in Adobe XD with the quick mockup plugin. The design has evolved somewhat as I have been implementing and testing it.

- Overall styling: Removing default margins/padding/borders, adding basic backround color,text styles and display properties to the Body through selecting Body/Header/Main/Footer.
- Custom styling on some elements, several hover effects have been used in the Header, Main and Footer section of the Body many of these have been removed or modified for smaller screens via media queries.
- The Landing Page and Destination pages only differ in gallery containers and hover effects used with those gallery containers.
- No back button are included in the design intentionally the user can return to the top of the page by clicking on the 'Nomada Photography' heading at the bottom of the page and then use the navigation menu.
- Image files were also not further compressed intentionally as this is a Photography Portfolio and maintaining the integrity of the colors and quality of the image takes priority over slightly longer loading times.

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

- Design Review Prototype in Adobe XD: <https://xd.adobe.com/view/4d002e9a-15fe-4078-863d-420e3ac33da3-1853/>

- Wireframes imported into Figma: <https://www.figma.com/file/Vz4TudFv2r2o7fMv8JYdDF/Nomada-Photography?type=design&node-id=0%3A1&t=55xebaSEyXd1LKoy-1>

Main Landing Page Wireframe:

![Main Gallery Landing Page Wireframe](/docs/images/photography_%20home.jpg)

## Technology

Technology used in this project is as follows:

- CSS
- HTML
- Code Institute Repo Template
- VScode
- Adobe XD
- Figma
- Git
- GitHub
- Gitpages

## Code

All pages:

- HTML boilerplate for all pages to start then used custom HTML, styled using CSS flexbox. All pages have the same Head, Header and Footer.

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
     - The menu items are links with their own styling, including a hover effect and the option to set one as active.
     - The #logo element has been left as an id instead of class so it can be reference in links in the .hero-image-container section as well and the Footer .footer-text-container.
     - The menu section is also a flex container and has its font size and letter spacing set. Each menu item is styled without bullets and with some margin between them. The menu items are links with their own styling, including a hover effect and the option to set one as active.

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

About Page description of Code and Content (about.html):

- Head: Same content as the Gallery Landing and Destination Pages.

  - Body: Header (different hero image) and Footer are the same as the Gallery Landing and Destination Pages.

  - Main: The section is divided into two parts: a text area and an image area.

      1. About Body Container
         - The entire section is contained within a section container element with class name "about-body-container", with a maximum width of 1200 pixels, centered horizontally on the page with margins set to 0, and aligned vertically with the center of the page using flexbox properties.
      2. About Textbox
         - The text area is divided into a h3 heading with class name "about-heading" and a div body of text with class name "about-textbox". The heading is styled with a large, bold font and a primary text color. The body of text is styled with a smaller font and a secondary text color.
      3. About Image Grid
         - The image area is divided into two rows: a row of smaller images with class name "about-small-images" and a single larger image with class name "bottom-image" beneath them.
         - The smaller images are arranged in a row with a gap of 10 pixels between them and are each no wider than a certain width, with each image contained within an img tag with class name "about-small-images img". The larger image is twice the width of the smaller images and has a maximum height of 200 pixels, contained within an img tag with class name bottom-image img.

  Contact Page description of Code and Content (contact.html):

  - Head: Same content as the Gallery Landing and Destination Pages.

    - Body: Header (different hero image) and Footer are the same as the Gallery Landing and Destination Pages.

      - Main

        1. Contact Form Container - The form is contained within a forum element with the class "contact-form-container", which is styled to be centered, have a width of 50%, and a border of 20px with a color defined by the variable "--secondary-color". The form itself is within a div with the class "contact-form", which has a background color defined by the variable "--background-color", a maximum width of 40%, and padding of 2em. The form title, defined by an h5 element with the class "contact-title", is styled to have a font family of "--primary-font", be bold and have a font size of 34px.

        2. Contact Form Image - An image is also included in the form, within a div with the class "contact-form-image". The image is centered and has a maximum width of 50%.

        3. Contact Forum - This form is a dummy forum setup with GET and an action that will redirect the user back to contact.html essentially reloading the page. The Name, Email and Message text input fields are all required to be completed before the form can be submitted. - Text inputs within the form, defined by elements with the class "text-input-contact", have a font family of "--primary-font", regular font weight, font size of 16px, and a color defined by the variable "--text-color-secondary". The input fields have a width of 100%, height of 25px, and a margin of 5px 0 20px 0. They also have a border of 3px with a color defined by the variable "--text-color-secondary" and a border radius of 3px. - The message input field, defined by an element with the class "message", has the same styling as the text input fields, but with a height of 150px. - When the input fields are in focus, they have an outline removed and a border color of "--accent-color". - The submit button has the class "submit-button" and has a width of 100%, box-sizing of border-box, margin-top of 2%, border radius of 2px, and padding of 1em. Its font size is set to 100%, and it has a background color defined by the variable "--accent-color" and text color defined by the variable "--main-color". The button is displayed as a block element. The submit button also has a hover effect that changes it's color.

  Thank You Page description of code and content (thank_you.html):

  - Head: Same content as the Gallery Landing and Destination Pages.

    - Body: Header (different hero image) and Footer are the same as the Gallery Landing and Destination Pages.
  
      - Main:

        1. Heading: The section begins with an h4 element displaying a hash symbol (#). This can be replaced with a relevant heading or icon to represent the purpose of the "Thank you page."

        2. Image: Following the heading, there is a div element with a class of "thank-you-image" containing an img element. The image displayed is specified by the "src" attribute of the img tag. It is recommended to replace the placeholder image URL ("assets/images/howth_view.jpeg") with a relevant image related to the website or the action that led to the "Thank you page."

Text and Message: Below the image, there is another div element with a class of "thank-you-text-container." This container holds the content to convey appreciation and provide additional information to the users. It consists of an h5 element with a class of "thank-you-heading" displaying the text "Thank you!" This heading can be customized to fit the website's branding and messaging. Below the heading, there is a p element with a class of "thank-you-text" containing a message thanking the user for their action and assuring them that someone will be in touch shortly. Additionally, it suggests following the website on social media. You can customize the message and include relevant details to enhance the user's experience.

    - Media Queries:
      These media queries are used to apply different styles and layout adjustments to the elements on a webpage based on the size of the screen or device being used to view the page. Here is a breakdown of each media query:

    1. For screens 1200px:

       - Targets the main index page image grid.
        Adjusts the grid template columns, rows, row gap, and padding of the .gallery-container element.

    2. For screens 1078px:

       - Targets heading elements with classes .about-heading, .contact-title, and .thank-you-heading.
       Adjusts the font size and text alignment of the headings.

    3. For screens 885px:

        - Targets the image grids on the main index page.
        Adjusts the grid template columns, rows, row gap, padding, and flex properties of .gallery-container and .gallery-container2 elements.
        Modifies various styles for text overlays, text boxes, and images on the about page.
        Changes the font size of .about-heading to 36px.
        Adjusts the layout of images and elements on the about page and contact page.

    4. For screens 768px:

        - Targets the thank you page container.
        Adjusts the padding and max-width of .thank-you-text-container.
        Modifies various styles for header elements, logo, navigation menu, hero image, image overlays, text overlays, contact form, and thank you page elements.

    5. For screens 480px:

        - Modifies various styles for header elements, logo, hero image, text overlays, and image overlays.
        Adjusts font size, max-height, and width of certain elements.

    6. Query targets devices that can hover:

        - Applies hover effects and transitions to certain elements when hovering.
          Adjusts that adjust opacity and color on hover for image overlays, social network icons, footer text, and submit button.

    7. Non-touch tap-reveal and overlay settings:

        - Applies overlay and tap-reveal effects to certain elements on touch devices.
          Adjusts opacity and styles for image overlays and text overlays on tap or focus.
          Excludes overlay from hero images.
          Modifies styles for gallery columns and text overlays on tap or focus.

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:

1. In the GitHub repository, on the Code page navigate to the Environments section on the righthand side of the page.
2. Click on github pages, this will take you to deployments history where you willl be able to click on 'view deployment'.
   The live link can be found here - [Link to Site Here](https://github.com/emidombek/nomada-photo)

## Testing

Validation:

- Passed the W3C HTML validator with one warning regarding aria-labels for a element in the .middle class however I will be leaving the aria labels as I believe they are essential for the UX of the site.
 -Passed the W3C CSS Validator/Jigsaw. 18 warnings received, 17 in regards to CSS variables not being checked. 1 in regards to the usage of the -ms-transform vendor extension.

Responsiveness:

1. The site was tested on the following devices:

- Android:

  - Samsung Galaxy S20
  - Xiaomi Mi 11i
  - Huawei P20 PRO
  - Huawei P30 PRO
  - Google Pixel5
  - Oneplus Nord 2
  - Galaxy Z Flip3
  - OPPO Find X3 PRO
  - Galaxy A12
  - Google Pixel 6 PRO
  - Xiaomi 12

- iPhones:

  - iPhone 5
  - iPhone SE 2016
  - iPhone X
  - iPhone XR
  - iPhone 11
  - iPhone 11 PRO
  - iPhone 11 PRO MAX
  - iPhone 12 Mini
  - iPhone 12
  - iPhone 12 MAX
  - iPad Mini
  - iPad Air 4
  - iPad PRO 11
  - Galaxy Tab S7
  - Microsoft Surface Duo

- Laptops/PC screens:
  - MacBook Air 13in
  - MacBook Pro 13in
  - Dell 24in Monitor
  - HP 24in Monitor

## Known Issues and Bugs

- The hover underline element in the main Navigation Menu is not centered on some smaller screens.
- The additional hover dropdown menu was removed as it had too many issues with responsiveness and was not essential to the UX of the site.
- There were several issues with my Commit Messages due to lack of training of how/format these messages within the course.I have now corrected these issues and am citing this here as I am aware of the importance of these messages.

## Resources

- Content:
  - All photos used on this website were taken by me, Emilia Dombek.
  - Wireframes were made using the Quickmockup Plugin in Adobe XD.

- Code and Implementation:
  - VSCode, Git, GitHub and Gitpages were used to code and deploy the website. I used the Code Academy Template to create my repo on GitHub.

- Learning Resources:
  - W3 schools for CSS
  - CSS flexbox knowlegde and concepts were mostly learned from: Kevin Powell's Youtube Channel <https://www.youtube.com/@KevinPowell>
  - Stack Overflow posts to help with understanding bugs and media queries.
