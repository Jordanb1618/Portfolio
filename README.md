# Personal Portfolio Website

A modern, responsive single-page portfolio website with smooth scrolling and interactive animations.

## Features

- Clean and modern design
- Responsive layout that works on all devices
- Smooth scrolling navigation
- Interactive timeline for experience section
- Animated elements on scroll
- Contact section with social media links
- Customizable color scheme

## Customization

### 1. Personal Information

Edit the `index.html` file to update your personal information:

- Replace "Your Name" with your actual name
- Update the subtitle with your profession
- Add your experience details in the timeline section
- Update your education and skills in the resume section
- Add your contact information and social media links

### 2. Colors

You can customize the color scheme by modifying the CSS variables in `styles.css`:

```css
:root {
  --primary-color: #2c3e50; /* Main color */
  --secondary-color: #3498db; /* Accent color */
  --text-color: #333; /* Text color */
  --background-color: #f5f6fa; /* Background color */
}
```

### 3. Images

To add your profile picture or project images:

1. Create an `images` folder in the root directory
2. Add your images to the folder
3. Update the image paths in the HTML file

### 4. Social Media Links

Update the social media links in the contact section of `index.html`:

```html
<div class="social-links">
  <a href="your-github-url" class="social-link"
    ><i class="fab fa-github"></i
  ></a>
  <a href="your-linkedin-url" class="social-link"
    ><i class="fab fa-linkedin"></i
  ></a>
  <a href="your-twitter-url" class="social-link"
    ><i class="fab fa-twitter"></i
  ></a>
</div>
```

## Running the Website

1. Clone this repository or download the files
2. Open `index.html` in your web browser
3. For development, you can use a local server (e.g., Live Server in VS Code)

## Browser Support

The website is compatible with all modern browsers:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Technologies Used

- HTML5
- CSS3 (with CSS Variables and Flexbox/Grid)
- JavaScript (ES6+)
- Font Awesome Icons

## License

This project is open source and available under the MIT License.
