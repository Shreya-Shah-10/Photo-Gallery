- 👋 Hi, I’m @Shreya-Shah-10
- 💞️ I’m interested in coding..
- ⚡ I’m currently making projects...

  # Photo-Gallery
* Here's a detailed breakdown of your Photo Gallery code, explaining how it works and the functionality of each section:

# HTML Structure

1.Document Declaration:
- This indicates that the document is an HTML5 document.
2.Head Section:
- Sets the character encoding to UTF-8.
- Ensures the webpage is responsive on different devices.
- Includes a description for SEO and links to an external CSS file for styling.
3. Header:
- Displays the main title and a brief description of the gallery.
4. Gallery Section:
- Contains thumbnail images wrapped in anchor tags (<a>).
- Each anchor links to a corresponding lightbox (#img1, #img2, etc.) for full-size viewing.
5. Lightbox for Full-Size Images:
- Each lightbox is a full-sized version of the image.
- Contains a close button (&times;) that allows users to exit the lightbox view.
6. Footer:
- Displays copyright information at the bottom of the page.

# CSS Styling
1. Body:
- Sets the font, removes default margins and padding, and specifies a background color.
2. Header:
- Styles the header with a background color and text alignment.
3. Gallery Layout:
- Utilizes CSS Grid to create a responsive gallery layout.
- Thumbnails will adjust based on the screen size.
4. Image Styling:
- Sets the images to scale up slightly when hovered, enhancing user interaction.
5. Lightbox Styling:
- The lightbox is initially hidden (display: none;).
- When the lightbox is targeted (via anchor link), it becomes visible (display: flex;).
6. Close Button:
- Positions the close button in the top right corner of the lightbox.
7. Footer:
- Styles the footer with a background color, text color, and padding.

==> How It Works
* Thumbnail Interaction: When a user clicks on a thumbnail image, the corresponding lightbox is activated, displaying the full-sized image.
* Lightbox Functionality: The lightbox overlays the entire viewport, allowing the user to see the image clearly against a dark background. Clicking the close button or anywhere outside the image closes the lightbox.
* Responsive Design: The gallery layout and images adapt to various screen sizes, ensuring a user-friendly experience on both desktop and mobile devices.

==> Summary
* This code creates a simple and effective photo gallery with a responsive layout, providing an interactive way for users to view images. The combination of HTML and CSS allows for a clean design and smooth functionality, making it an excellent foundation for a photo gallery application.






