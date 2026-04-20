# Assets Directory

This folder contains all static assets for the Cursopy website.

## Structure

- **images/** - Store all images, icons, and graphics here
- **fonts/** - Custom fonts (if not using Google Fonts)
- **videos/** - Video files for courses
- **icons/** - SVG icons for UI elements

## Usage

Reference assets from the main HTML files using relative paths:

```html
<img src="assets/images/course-banner.jpg" alt="Course Banner">
<video src="assets/videos/intro.mp4"></video>
```

## Guidelines

- Keep image files optimized for web (use compression tools)
- Name files descriptively (e.g., `python-course-hero.jpg` instead of `img1.jpg`)
- Document new assets as you add them