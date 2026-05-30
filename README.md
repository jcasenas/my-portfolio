# Portfolio — Systems · Design · Motion

A clean, responsive portfolio website built with vanilla HTML, CSS, and JavaScript.

## File Structure

```
portfolio/
├── index.html              ← Main portfolio page
├── assets/
│   ├── css/
│   │   └── style.css       ← All styles + dark mode
│   ├── js/
│   │   └── main.js         ← Cursor, slideshows, tabs, animations
│   └── img/                ← Put your images here
│       ├── hero-photo.jpg
│       ├── about-photo.jpg
│       ├── project-1.jpg   (etc.)
│       └── design-1.jpg    (etc.)
└── README.md
```

## How to Customize

### 1. Your Name & Info
- Open `index.html`
- Search for `Your Name` and replace throughout
- Update `[Your City]`, email, and social links

### 2. Hero Photo
Replace the placeholder div with:
```html
<img src="assets/img/hero-photo.jpg" alt="Your Name">
```

### 3. Adding Project Screenshots to Slideshows
For each `<div class="slide">`, replace the gradient background div with:
```html
<div class="slide-bg" style="background-image: url('assets/img/your-screenshot.png');"></div>
```

### 4. Systems Section — Card Details
Edit each `.sys-card` with your real project names, descriptions, and tech tags.

### 5. Skills & About
Edit the `#about` section text and the `.skill-item` list items.

### 6. Contact Links
Update email, LinkedIn, GitHub, and Instagram URLs in the `#contact` section.

### 7. CV Download
Place your PDF as `assets/your-cv.pdf` — the download button is already wired up.

## Sections

| Section | ID | Purpose |
|---|---|---|
| Hero | `#home` | Intro with typewriter role animation |
| Systems | `#systems` | Slideshow + cards grid with tab filter |
| Graphic Design | `#graphics` | Slideshow with category tabs |
| Motion & 3D | `#motion` | Slideshow with tool chips |
| About | `#about` | Bio, skills, photo |
| Contact | `#contact` | Links + contact form |

## Features
- Dark / Light mode (persisted in localStorage)
- Custom cursor with hover effects
- Scroll-reveal animations
- Tab filtering for each section
- Auto-playing slideshows with swipe support
- Typewriter role animation in hero
- Fully responsive (mobile hamburger menu)
- Smooth scroll navigation with active link tracking

## Running Locally
Just open `index.html` in a browser — no build step needed.
For the Google Fonts to load, you'll need an internet connection.
