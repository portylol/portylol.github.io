# Personal Portfolio Website

This is a personal portfolio website template that you can use to create your own online portfolio. It includes sections for an about page, portfolio items, and a contact form. This README provides information on how to set up and customize the website.

## Table of Contents

- [Features](#features)
- [Customization](#customization)
- [Adding Portfolio Items](#adding-portfolio-items)
- [Contributing](#contributing)
- [License](#license)

## Features

- Simple and responsive design.
- Smooth scrolling navigation.
- Portfolio section with filter functionality.
- Contact form for inquiries.

## Customization

To customize this website for your personal use, follow these steps:

### Edit the content:

Modify the text and content in the HTML file (index.html) to reflect your personal information, skills, and projects.

### Update images:

Replace the placeholder images in the img folder with your own project images. Make sure to update the src attributes in the HTML accordingly.

### Styling:

Customize the CSS in the style.css file to match your desired colors and styles.

### JavaScript:

Modify the JavaScript in the script.js file to add or remove functionality as needed.

## Adding Portfolio Items

To add more portfolio items to your website, simply follow these steps:

- Add a new HTML block for your portfolio item in the index.html file. Make sure to specify the appropriate category using the data-category attribute.

```html
<div class="portfolio-item web-design">
    <img src="project6.jpg" alt="Project 6">
    <h3>Project 6</h3>
    <p>Description of the project.</p>
</div>
```

Customize the content and image for your new portfolio item.

If you've added a new category, make sure to update the filter buttons in the index.html and script.js files accordingly.

```html
<button class="filter-button" data-category="your-category">Your Category</button>
```

```javascript
document.querySelectorAll('.filter-button').forEach(button => {
    // Add your category filter handling here
});

Remember to replace placeholders such as `your-username`, `your-demo-link`, `your-image.jpg`, and `your-category` with your actual information and URLs. This README file serves as documentation for your project and helps others understand how to use.
