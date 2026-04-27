# Loading-Animation-3

Loading Animation Built Using HTML and CSS.


## Demo

![Loading Animation Preview](https://raw.githubusercontent.com/BinaryVortex/Loading-Animation-3/main/Screenshot%202024-07-02%20183312.png)


## Overview

A simple, lightweight loading animation created with pure HTML and CSS. This project demonstrates how to build a rotating ring loader with color-shifting box-shadows and animated loading text. It’s ideal as a starting point for learning CSS animations or dropping into small projects.


## Features

- No JavaScript — only HTML and CSS
- Smooth rotation and color transitions
- Minimal, easy-to-read code (single HTML + CSS file)
- Easily customizable size, colors, and speed


## Files

- `index.html` — markup for the loader
- `style.css` — styling and animations
- `Screenshot 2024-07-02 183312.png` — preview image used in this README


## Usage

1. Clone or download the repository.

   git clone https://github.com/BinaryVortex/Loading-Animation-3.git

2. Open `index.html` in your browser (no build tools required).


## Customization

You can change the animation by editing `style.css`:

- Size: update `.ring` width/height (currently 200px).
- Speed: change `animation: ring 2s linear infinite;` to a different duration.
- Colors: modify the `box-shadow` color stops inside `@keyframes ring`.
- Text animation: adjust the `@keyframes text` block for different effects.


## Notes

- The project uses the Montserrat font in CSS; include the font or change `font-family` if you prefer a fallback.
- No license file is included — add a LICENSE if you want to specify reuse terms.


## Credits

Created by Disandu Perera (as noted in the HTML file). If you'd like improvements or variations, feel free to open an issue or submit a PR.
