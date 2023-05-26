# Nomada Photography Readme

![Devices Preview](/docs/images/nomada_photo_preview_screen.png)

[Link to Live Site Here](https://github.com/emidombek/nomada-photo)

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

  - After the user clicks the link the page jumps down to the Logo Banner where the logo of the Photographer is seen as well as a Navigation Menu (the page layout has been modified for mobile devices and other devices that respond to touch). The gallery of the main body is also partially visible this is meant to entice the user to scroll through. There are eight photos in total of different destinations in this gallery that lead to 8 destination pages when the photo is clicked on or tapped, on devices that can hover an icon will appear that can be clicked on non-hover devices the icon will be displayed immediately.

  - At the bottom of every page is a footer with social media links and a 'Nomada Photography' link that takes the user back to the top of the Logo Banner where the Navigation Menu is. Underneath this is the copyright text.

     <details>
       <summary>Click here to view screenshot of the Main Gallery Landing Page</summary>
  
       ![Main Gallery Landing Page Screenshot](/docs/images/home_full_screen.png)
  
       </details>

     <details>
       <summary>Click here to view demo of the Main Gallery Landing Page</summary>
  
       ![Main Gallery Demo](/docs/images/home_demo_AdobeExpress.gif)
  
       </details>
  
  2. Destination Pages

  - The Destination Pages allow the user to view an additional 4 images from the selected destination. There is a hover/tap to reveal that allows users to view information on where and when the photo was taken:

     <details>
      <summary>Click here to view screenshot of the Destination Gallery Page</summary>

       ![Destination Page](/docs/images/destination_page_full.png)

       </details>

    <details>
     <summary>Click here to view demo gif of the Destination Gallery Page</summary>

      ![Destination Page Demo](/docs/images/destinationpage_demo_AdobeExpress.gif)

     </details>

    - The Destination Pages differ only in text descriptions and images. The HTML/CSS is the same on each page besides the different image files and text.

  3. About Page

     - The About Page contains a small gallery of selected images and a small about section:

   <details>
    <summary>Click here to view demo gif of About Page</summary>

       ![About Page Demo](/docs/images/about_demo_AdobeExpress.gif)
       </details>

       <details>
       <summary>Click to view full screenshot of About Page</summary>
  
       ![About Page Screenshot](/docs/images/about_full_screen.png)
   </details>

  4. Contact Page

     - The Contact Page includes a dummy webform:

       ![Contact Page](/docs/images/contact_fullscreen.png)

  5. Thank You Page

     - The user is redirected to this page when submitting a message via the Contact Form.

       <details>
       <summary>Click to view a demo gif of the Contact Page & Thank You Page</summary>
  
      
       ![Contact & Thank You Page Demo](/docs/images/contact_demo_AdobeExpress.gif)
       </details>

       <details>
       <summary>Click to view a full screenshot of the Thank You Page</summary>
  
      
       ![Thank You Page](/docs/images/thank_you_full_screen.png)
       </details>

## Design and Layout

The design for the website was created in Adobe XD with the quick mockup plugin, wireframes were imported into Figma for ease of viewing and sharing. The design has evolved somewhat as I have been implementing and testing it for responsiveness. The original idea was to create and lightbox type gallery with just the 8 photos but this idea soon evolved into a per page mini gallery for each destination with an additional 4 photos as I was implementing the website. This allowed for sharing of more work and a travel-destination like experience for the user. 

- Overall styling: Removing default margins/padding/borders, adding basic backround color,text styles and display properties to the Body through selecting Body/Header/Main/Footer.
- Custom styling on some elements, several hover effects have been used in the Header, Main and Footer section of the Body many of these have been removed or modified for smaller screens via media queries.
- The Landing Page and Destination pages only differ in gallery containers and hover effects used with those gallery containers.
- No back button are included in the design intentionally the user can return to the top of the page by clicking on the 'Nomada Photography' heading at the bottom of the page and then use the navigation menu.
- Image files were also not further compressed intentionally as this is a Photography Portfolio and maintaining the integrity of the colors and quality of the image takes priority over slightly longer loading times.
- For devices that are not able to hover I have either fixed the image overlays to show or created a click to show effect.

- Primary Design System is as follows:

  1. --font-family: Raleway, sans-serif, Source Serif Pro, sans-serif;
  2. --primary-font: Raleway, sans-serif;
  3. --secondary-font: Source Serif Pro, sans-serif;
  4. --main-color: white;
  5. --background-color: white;
  6. --primary-color: #D8D5BF;
  7. --secondary-color: #AEC1BA;
  8. --accent-color: #CF755A;
  9. --text-color-primary: #000000;
  10. --text-color-secondary: #464646;
  11. --text-color-accent: #CF755A;
  12. --text-color-secondary-accent: #737373;
  13. --line-height: 1.5;

High Fidelity Wireframes and a Prototype that have been created in Adobe XD can be found here:

- [Design Review Prototype in Adobe XD](https://xd.adobe.com/view/4d002e9a-15fe-4078-863d-420e3ac33da3-1853/)

- [Wireframes imported into Figma from Adobe XD](<https://www.figma.com/file/Vz4TudFv2r2o7fMv8JYdDF/Nomada-Photography?type=design&node-id=0%3A1&t=55xebaSEyXd1LKoy-1>)

Main Landing Page wireframe:

   <details>
   <summary>Click to view the Main Gallery Landing Page Wireframe</summary>
  
      
   ![Main Gallery Landing Page Wireframe](/docs/images/photography_%20home.jpg)
   </details>

Screenshot of all the wireframes in Figma:

   <details>
   <summary>Click to view screenshot of Figma Wireframes</summary>
  
      
   ![Screenshot of Wireframes in Figma](/docs/images/figma_wireframe_screen.png)
   </details>

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

**All pages:**

- HTML boilerplate for all pages to start then used custom HTML, styled using CSS flexbox. All pages have the same Head, Header and Footer.

**Gallery Landing and Destination Pages description of Code and Content:**

(Landing page: index.html) (Destination pages: chelmno.html, connemara.html, tatra.html, torun.html, richmond.html, bydgoszcz.html, slieveleague.html, gdansk.html)

- Head

  1. Contains Metadata for website.
  2. Contains website title.

- Body

  - Header

  1. Hero Image
     <details>
     <summary>Click to view Hero Image Details & Code Description</summary>

     - Unusally large hero image which allows the user to experience the photo in fullscreen with hover elements then give context and allow the user to jump further down to the menu section. This has been modified for smaller screens to ensure good UX.
     - The .hero-image class centers and sizes the image container, while the .hero-image img class sets the properties of the image itself.
     - The .image-overlay class creates a darkened overlay effect that can be used with both hero images.
     - The .text-overlay class styles text contained within the image overlay, and the .middle class adds a link that allows users to jump to the menu section of the page.
     - The .text-box-hover class creates a box-like appearance when the user hovers over it.

     - Screenshot of the HTML markup used for the Hero Image and the overlays:

     ![Screenshot of HTML markup used for Hero Image](/docs/images/rename_hero_image_html.png)

     - Screenshot of the CSS markup used for the Hero Image:

     ![Screenshot of part of the CSS used for Hero Image](/docs/images/hero_image_css.png)

     - Note: CSS styling for the overlays can be found in the same section of the CSS file.

     </details>

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
     <details>
     <summary>Click to view Gallery Settings for the Main Landing Page and Destination Pages, Code Screenshots & Code Description</summary>

     - The gallery container for the Main Landing Page uses grid display to organize its images in columns and rows, with specific column width, row height, column gap, and row gap. This container is used to display the 8 images with corresponding links that lead the user to the destination pages.
     - The gallery-container2 for the Destination Gallery Pages has a different row height setting that repeats twice and ensures an equal amount of space in the container is occupied by the rows. This container is used to display the 4 images on the destination pages.
     - The h4 element is set to display none, which means it won't be visible in the gallery.
     - The images in the gallery columns are set to object-fit: cover, which means they will scale and crop to fill the available space while maintaining their aspect ratio, and object-position: top is used to align the images at the top of the container.
     - The image-overlay and image-overlay2 classes are used to create an overlay on the images, with a semi-transparent black background and centered text.
     - The gallery-column i and gallery-column-center i classes define an icon for the gallery columns, which is set to the main color.
     - Finally, the text-overlay2 class is used to create a text overlay on top of the images, positioned at the center of the container.

     - Screenshot of the HTML markup used for the Main Landing Page Gallery and the overlays:

     ![Screenshot of HTML markup used for Main Landing Page Gallery](/docs/images/main_gallery_screenshot.png)

     - Screenshot of the HTML markup used for the Destination Gallery Pages and the overlays:

     ![Screenshot of HTML markup used for Destination Page Gallery](/docs/images/destination_gallery_html.png)

     - Screenshot of the CSS used for the Gallery Grids:

     ![Screenshot of part of the CSS used for Main Landing Page Gallery](/docs/images/main_destination_gallery_css.png)

     - Screenshot of CSS setting used for Destination Gallery Grid Rows:

     ![Screenshot of part of the CSS used for Destination Page Gallery](/docs/images/destination_gallery_row_setting.png)

     - Note: CSS styling for the various gallery overlays and image settings can be found in the same section of the CSS file.

     </details>

  - Footer

  1. Footer Banner
     <details>
      <summary>Click to view Footer Banner Settings, Code Screenshots & Code Description</summary>

     - The Footer Banner is a larger banner that contains social media icons that link to different social media sites. There is also a heading that links to the #logo at the top of the page which takes the user back to the menu when selected.
     - The footer container (footer-text-container) is positioned absolutely and arranged as a vertical column. It has a background color and text color specified.
     - The main footer text (footer-text) has a background color, bold font, and centered alignment. It transitions smoothly when its color changes via hover effect.
     - The copyright text (copyright-text) has a specific color, font, and alignment.
     - Social network icons (social-networks) are displayed as a horizontal list in the center. Each icon has some margin around it.
     - The social network icon elements (social-networks i) have a larger font size, centered alignment, and a specific color. They also transition smoothly when their color changes via hover effect. The social network list code was taken from the Love Running Project.

     - Screenshot of the HTML markup used for the Footer Banner and the overlays:

     ![Screenshot of HTML markup used for Footer Banner](/docs/images/footer_banner_html.png)

     - Screenshot of the CSS used for the Footer Banner:

     ![Screenshot of part of the CSS used for Footer Banner](/docs/images/footer_banner_css.png)

     - Note: CSS styling for the social media icons and list items can be found in the same section of the CSS file.

     </details>

**About Page description of Code and Content (about.html):**

- Head: Same content as the Gallery Landing and Destination Pages.

  - Body: Header (different hero image) and Footer are the same as the Gallery Landing and Destination Pages.

  - Main: This section contains a heading, a mini image gallery and a text area.

     <details>
      <summary>Click to view About Page Settings, Code Screenshots & Code Description</summary>

     - The entire section is contained within a section container element with class name "about-body-container", with a maximum width of 1200 pixels, centered horizontally on the page with margins set to 0, and aligned vertically with the center of the page using flexbox properties.
     - The text area is divided into a h3 heading with class name "about-heading" and a div body of text with class name "about-textbox". The heading is styled with a large, bold font and a primary text color. The body of text is styled with a smaller font and a secondary text color.
     - The image area is divided into two rows: a row of smaller images with class name "about-small-images" and a single larger image with class name "bottom-image" beneath them.
     - The smaller images are arranged in a row with a gap of 10 pixels between them and are each no wider than a certain width, with each image contained within an img tag with class name "about-small-images img". The larger image is twice the width of the smaller images and has a maximum height of 200 pixels, contained within an img tag with class name bottom-image img.

     - Screenshot of the HTML markup used for the About Page Main Element:

     ![Screenshot of HTML markup used for the About Page](/docs/images/about_page_main_html.png)

     - Screenshot of the CSS used for the About Page Container:

     ![Screenshot of part of the CSS used for the About Page Container](/docs/images/about_page_css.png)

     - Screenshot of the CSS used for the About Page Gallery:

     ![Screenshot of part of the CSS used for the About Page Gallery](/docs/images/about_page_gallery_css.png)

     </details>

**Contact Page description of Code and Content:**

- Head: Same content as the Gallery Landing and Destination Pages.

  - Body: Header (different hero image) and Footer are the same as the Gallery Landing and Destination Pages.

  - Main: The section contains a heading,form and an image.
    
     <details>
      <summary>Click to view Contact Page Settings, Code Screenshots & Code Description</summary>

      - Contact Form Container - The form is contained within a forum element with the class "contact-form-container", which is styled to be centered, have a width of 50%, and a border of 20px with a color defined by the variable "--secondary-color". The form itself is within a div with the class "contact-form", which has a background color defined by the variable "--background-color", a maximum width of 40%, and padding of 2em. The form title, defined by an h5 element with the class "contact-title", is styled to have a font family of "--primary-font", be bold and have a font size of 34px.

      - Contact Form Image - An image is also included in the form, within a div with the class "contact-form-image". The image is centered and has a maximum width of 50%.

      - Contact Forum - This form is a dummy forum setup with GET and an action that will redirect the user back to contact.html essentially reloading the page. The Name, Email and Message text input fields are all required to be completed before the form can be submitted. - Text inputs within the form, defined by elements with the class "text-input-contact", have a font family of "--primary-font", regular font weight, font size of 16px, and a color defined by the variable "--text-color-secondary". The input fields have a width of 100%, height of 25px, and a margin of 5px 0 20px 0. They also have a border of 3px with a color defined by the variable "--text-color-secondary" and a border radius of 3px. - The message input field, defined by an element with the class "message", has the same styling as the text input fields, but with a height of 150px. - When the input fields are in focus, they have an outline removed and a border color of "--accent-color". - The submit button has the class "submit-button" and has a width of 100%, box-sizing of border-box, margin-top of 2%, border radius of 2px, and padding of 1em. Its font size is set to 100%, and it has a background color defined by the variable "--accent-color" and text color defined by the variable "--main-color". The button is displayed as a block element. The submit button also has a hover effect that changes it's color.

      - Screenshot of the HTML markup used for the Contact Page Main Element:

      ![Screenshot of HTML markup used for the Contact Page](/docs/images/contact_page_html.png)

      - Screenshot of the CSS used for the About Page Container:

      ![Screenshot of part of the CSS used for the Contact & Thank You Page](/docs/images/contact_page_css.png)

     </details>

**Thank You Page description of code and content (thank_you.html):**

- Head: Same content as the Gallery Landing and Destination Pages.

  - Body: Header (different hero image) and Footer are the same as the Gallery Landing and Destination Pages.
  
  - Main: This section contains a heading, 
    
     <details>
     <summary>Click to view Thank You Page Settings, Code Screenshots & Code Description</summary>

     - Heading: The section begins with an h4 element displaying a hash symbol (#). This can be replaced with a relevant heading or icon to represent the purpose of the "Thank you page."

     - Image: Following the heading, there is a div element with a class of "thank-you-image" containing an img element.

     - Text and Message: Below the image, there is another div element with a class of "thank-you-text-container." It consists of an h5 element with a class of "thank-you-heading" displaying the text "Thank you!" Below the heading, there is a p element with a class of "thank-you-text" containing a message thanking the user.

     - Screenshot of the HTML markup used for the Thank You Page Main Element:

     ![Screenshot of HTML markup used for the Contact Page](/docs/images/contact_page_html.png)

     - Screenshot of the CSS used for the Thank You page:

     ![Screenshot of part of the CSS used for the Contact & Thank You Page](/docs/images/contact_page_css.png)

     </details>

 **Media Queries:**

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
   The live link can be found here - [Link to Live Site Here](https://github.com/emidombek/nomada-photo)

## Testing

Validation:

- Passed the W3C HTML validator with one warning regarding aria-labels for a element in the .middle class however I will be leaving the aria labels as I believe they are essential for the UX of the site.
- Passed the W3C CSS Validator/Jigsaw. 18 warnings received, 17 in regards to CSS variables not being checked. 1 in regards to the usage of the -ms-transform vendor extension.

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

- The additional hover dropdown menu was removed as it had too many issues with responsiveness and was not essential to the UX of the site.
- There were several issues with my Commit Messages due to lack of training of how/format these messages within the course I have been doing large commits and will be working on reducing these commits to smaller changes. I have now corrected these issues and am citing this here as I am aware of the importance of these messages.
- This website is a Photography Portfolio and is image heavy. Some images may be slow to load even after being compressed in Photoshop.

## Resources

- Content:


  - All photos used on this website were taken by me, Emilia Dombek.
  - Wireframes were made using the Quickmockup Plugin in Adobe XD. Wireframes have also been imported into Figma for ease of viewing.

- Code and Implementation:


  - VSCode, Git, GitHub and Gitpages were used to code and deploy the website. I used the Code Academy Template to create my repo on GitHub.
  - To test and view the website locally I used a VSCode extension called 'Live Server' by Ritwick Dey.
  - I used the 'Mobile Simulator' extension on Chrome to test on different devices for responsiveness.

- Learning Resources:


  - W3 schools for CSS
  - CSS flexbox knowlegde and concepts were mostly learned from: Kevin Powell's Youtube Channel <https://www.youtube.com/@KevinPowell>
  - Stack Overflow posts to help with understanding bugs and media queries.
  - My Code Institute mentor gave me several examples of code.

## Acknowledgements

