
# HORIZON — Interactive Day & Night Landscape

A beautifully animated day and night environment switch built entirely with HTML5 and CSS3.

## Overview

HORIZON is a CSS-only interactive landscape experience that allows users to transition between a bright daytime environment and a peaceful nighttime scene.

The project demonstrates advanced CSS styling, layered scenery, checkbox-based state management, transitions, and keyframe animations without using JavaScript.

## Features

- CSS-only day and night toggle
- Animated sun and crescent moon
- Twinkling stars
- Drifting clouds
- Layered mountain silhouettes
- Multiple rolling hills
- CSS landscape transitions
- CSS custom properties
- Checkbox and sibling combinator interaction
- Responsive layout
- Reduced-motion accessibility support

## Technologies

- HTML5
- CSS3
- CSS Custom Properties
- CSS Transitions
- CSS Keyframes
- CSS Selectors
- Flexbox
- CSS Grid

## Project Structure

```text
day-night-landscape-toggle/
├── index.html
├── styles.css
├── README.md
├── LICENSE
└── .gitignore
```

## Getting Started

1. Clone the repository.
2. Open the folder in Visual Studio Code.
3. Open `index.html` in your browser.
4. Click the toggle in the top-right corner of the landscape.

No JavaScript, package installation, or build process is required.

## Core CSS Techniques

### Checkbox State Management

A visually hidden checkbox controls the environment.

```html
<input type="checkbox" id="sky-toggle">

<div class="scene">
  <!-- Landscape -->
</div>
```

### Sibling Combinator

The checked state changes the scene:

```css
.sky-checkbox:checked ~ .scene {
  --sky-top: #101b3d;
  --sky-bottom: #394b78;
}
```

### CSS Variables

Custom properties make it possible to transition between different color palettes.

### Keyframe Animations

The sun rotates, stars twinkle, and clouds drift using CSS animations.

## Design Goals

- Create a visually engaging environment using CSS alone.
- Demonstrate state changes without JavaScript.
- Explore layered illustration techniques.
- Build a responsive and accessible experience.
- Practice advanced CSS animation and transitions.

## Limitations

This is a visual environment demonstration, not a real-time astronomical simulation. The sun, moon, stars, and clouds use illustrative CSS positioning and animation.

## Future Improvements

- Add additional seasonal environments.
- Introduce a sunrise and sunset transition.
- Create animated birds and fireflies.
- Add a landscape color theme selector.
- Explore more detailed CSS-only scenery.

## Author

**Stephen Oyugi**

Front-End Developer | AI Automation & Machine Learning Enthusiast

- GitHub: https://github.com/Regalson001
- LinkedIn: https://linkedin.com/in/stephenoyugi001

## License

This project is available under the MIT License.
