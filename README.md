# UIU Robotics Club Home Page

Single-page club site built with HTML/CSS and a small JS slideshow.

## Quick Start
1) Put the referenced images in the project root (see Assets). 2) Open `index.html` in a modern browser. No build steps.

## What’s Inside
- Header with nav and Font Awesome socials
- Hero intro with manual image slideshow
- Event cards grid
- “What We Do” highlight sections
- Brands strip and contact footer

## Tech
HTML5, CSS3, vanilla JS, Font Awesome CDN.

## Customize
- Swap nav `href`s, hero text, CTA, and event card content in `index.html`.
- Replace slideshow images and dots together; logic is in `script.js`.
- Tweak colors/typography in `style.css`; red accents are set there.
- Update footer contact info and brand logos.

## Assets
Referenced in `index.html` (root folder):
- Logo: `images.jpg`; Hero: `body.png`
- Slideshow: `cuterobot_sign.jpg`, `cute-robot-cat.jpg`, `meow.jpg`
- Events: `Robo_Cat_Avatar.jpg`
- Sections: `1stPic.png`, `2ndPic.png`, `3rdPic.png`, `4thPic.png`
- Brands: `UiuMarsRover.jpg`, `UIUCanSat.png`, `TXBD.png`, `wroBD.jpg`, `ict.jpg`, `PLab.png`

## Notes
- Slideshow is manual (arrows/dots call `plusSlides()` / `currentSlide()` in `script.js`).
- Layout is desktop-first; add responsive tweaks in `style.css` if needed.
