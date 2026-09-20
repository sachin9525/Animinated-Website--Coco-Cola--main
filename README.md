# Coca-Cola Animated Website

A Coca-Cola-themed front-end showcase built with HTML, CSS, and JavaScript. The site combines video backgrounds, scroll-driven animations, product detail pages, and an image carousel.

## Features

- Animated intro loader and expandable navigation menu.
- Video hero and product previews.
- Smooth scrolling and scroll-triggered transitions.
- Image effects and a swipeable gallery.
- Three separate product detail pages.
- Sign-up and login overlays.

This is a static front-end demo. Authentication, Google sign-in, shopping, and newsletter subscriptions are not connected to a backend.

## Tech stack

- HTML5, CSS3, and vanilla JavaScript.
- GSAP and ScrollTrigger for animation.
- Locomotive Scroll for smooth scrolling.
- Shery.js, Three.js, and ControlKit for visual effects and their supporting tools.
- Swiper for the image carousel.
- Remix Icon and local font files.

Libraries are loaded through CDN script and stylesheet tags. No npm installation or build step is required. An internet connection is needed for CDN dependencies and externally hosted images and videos.

## Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/sachin9525/Animinated-Website--Coco-Cola--main.git
   cd Animinated-Website--Coco-Cola--main
   ```

2. Serve the project folder using either option:

   - **VS Code:** Open the folder, install the Live Server extension if needed, then right-click the root `index.html` and select **Open with Live Server**. Use the address opened by the extension.
   - **Python 3:** Run the following command from the project folder, then open <http://localhost:8000>:

     ```bash
     python -m http.server 8000
     ```

     On Windows, `py -m http.server 8000` also works when the Python launcher is installed.

3. Use the **More details** buttons to explore the product pages.

## Project structure

```text
.
|-- index.html       # Main landing page
|-- style.css        # Main page styles
|-- script.js        # Animation and interaction logic
|-- Font/            # Local fonts
|-- part2/           # Coca-Cola Cherry detail page
|-- part 3/          # Cherry Vanilla Zero Sugar detail page
|-- part 4/          # Coca-Cola Vanilla detail page
|-- *.jpg / *.png    # Local image assets
|-- *.webp / *.mp4   # Additional image and video assets
|-- .gitignore
`-- README.md
```

Each product folder contains its own `index.html`, `style.css`, `script.js`, and supporting assets.

## Customization

- Edit the root `index.html` to change landing-page content and media references.
- Update `style.css` for typography, colors, and layout.
- Adjust `script.js` for animation timing and interactions.
- Edit files inside the product folders to update their individual pages.
- Keep asset filenames and relative paths in sync when replacing media or fonts.

## Author

Designed and developed by [Sachin Kumar](https://github.com/sachin9525).
