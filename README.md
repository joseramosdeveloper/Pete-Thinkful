# starter-pete-thinkful-portfolio
# Pete Thinkful | Artist Portfolio

This repository contains the HTML and CSS code for Pete Thinkful's artist portfolio website. The structure is organized into different sections, including:

- **About**: Information about Pete and his artistic interests.
- **Portfolio**: Showcase of Pete's projects displayed on a single row with project descriptions.
- **Contact**: Links to Pete's social media profiles.

## HTML and CSS Structure

- The HTML file (`index.html`) includes sections for About, Portfolio, and Contact.
- The CSS styles are defined in the `style.css` file, providing styling for responsiveness and aesthetics.

### Special Styling for Portfolio

Pete's projects are displayed on a single row with spacing between them using the following CSS:

```css
.projects-container {
  display: flex;
  justify-content: space-around; /* Adjust the spacing to your preference */
  margin-top: 20px; /* Add margin for spacing from other elements */
}

.project-description {
  font-size: 14px; /* Set the font size for project descriptions */
  margin-bottom: 15px;
}
