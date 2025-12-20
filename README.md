# Personal Portfolio Website

A responsive personal portfolio website showcasing professional skills, education, and projects. Built with HTML, CSS, and JavaScript, this portfolio features a modern design with smooth animations and interactive elements.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [Customization](#customization)
- [Responsive Design](#responsive-design)
- [External Libraries](#external-libraries)

## Features

- **Responsive Design**: Fully responsive layout that works on mobile, tablet, and desktop devices
- **Interactive Navigation**: Smooth scrolling navigation with active link highlighting
- **Animated Elements**: Scroll reveal animations for content elements
- **Typing Effect**: Dynamic text typing animation in the hero section
- **Project Showcase**: Dedicated section to display projects with descriptions
- **Education Timeline**: Clear presentation of educational qualifications
- **Skills Display**: Organized display of technical skills and competencies
- **Social Media Integration**: Links to LinkedIn, GitHub, and Telegram profiles
- **Resume Download**: Direct link to download the resume PDF

## Technologies Used

- **HTML5**: Markup language for structuring the content
- **CSS3**: Styling with modern features like Flexbox and animations
- **JavaScript**: Interactive functionality and DOM manipulation
- **Typed.js**: Library for creating typing text animations
- **ScrollReveal.js**: Library for scroll animations
- **Unicons**: Icon library for social media and UI icons

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # Custom styles
├── script.js           # JavaScript functionality
├── image.jpg           # Profile/avatar image
├── favicon.png         # Website favicon
├── Resume.pdf          # downloadable resume
├── bank.png            # Banking project thumbnail
├── salon.png           # Salon project thumbnail
├── stock.png           # Stock project thumbnail
└── README.md           # This file
```

## Setup Instructions

1. Clone or download the repository
2. Open `index.html` in a web browser
3. No build process required - works directly in the browser

To host online:
1. Upload all files to a web hosting service
2. Ensure all file paths remain intact
3. The website will be accessible via your domain

## Customization

### Personal Information
- Name: Modify the name in the header and hero section
- Profile Image: Replace `image.jpg` with your own image
- Social Links: Update the href attributes in the social icons section
- Resume: Replace `Resume.pdf` with your own resume

### Content Sections
- **Hero Section**: Update the name, typing text effects, and introduction paragraph
- **About Section**: Modify the about information and skills lists
- **Education Section**: Update educational qualifications and institution links
- **Projects Section**: Add/remove projects and update project descriptions

### Colors
Modify the color scheme in `style.css` under the `:root` selector:
```css
:root {
  --body-color: rgb(250, 250, 250);
  --color-white: rgb(255, 255, 255);
  --text-color-second: rgb(68, 68, 68);
  --text-color-third: rgb(30, 159, 171);
  --first-color: rgb(110, 87, 224);
  --first-color-hover: rgb(40, 91, 212);
  --second-color: rgb(0, 201, 255);
  --third-color: rgb(192, 166, 49);
  --first-shadow-color: rgba(0, 0, 0, 0.1);
}
```

## Responsive Design

The portfolio is fully responsive and adapts to different screen sizes:
- **Desktop (>1024px)**: Full layout with side-by-side content
- **Tablet (≤1024px)**: Adjusted spacing and slightly modified layout
- **Mobile (≤900px)**: Stacked layout with hamburger menu
- **Small Mobile (≤540px)**: Optimized spacing for small screens

Media queries are defined in `style.css` for:
- 1024px breakpoint
- 900px breakpoint (mobile menu activation)
- 540px breakpoint (small screen optimization)

## External Libraries

### Typed.js
Used for the typing text animation in the hero section.
```html
<script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
```

### ScrollReveal.js
Used for scroll animations throughout the site.
```html
<script src="https://unpkg.com/scrollreveal"></script>
```

### Unicons
Icon library for social media and UI icons.
```html
<link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.8/css/line.css">
```

## Browser Support

The portfolio works on all modern browsers that support:
- CSS3 Flexbox
- CSS3 Animations
- ES6 JavaScript
- Modern HTML5 features

Tested on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Author

**K Sakthi Priya**

- LinkedIn: [linkedin.com/in/sakthi-priya-a43966288](https://www.linkedin.com/in/sakthi-priya-a43966288)
- GitHub: [github.com/SakthiPriya-0510](https://github.com/SakthiPriya-0510)
- Telegram: [@sakthikrish](https://t.me/sakthikrish)

## License

This project is open source and available under the [MIT License](LICENSE).

Feel free to fork and customize this portfolio for your own use!