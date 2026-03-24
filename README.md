# Acceptance Criteria by Mentor

## Project

- **A1** There is an `images` folder in the root of the project containing images.
- **A2** All vector images (icons) are combined into an SVG sprite `icons.svg` located in the `images` folder.
- **A3** All vector images are optimized.
- **A4** There is a `css` folder in the root of the project with style files.
- **A5** All styles are written in a single file `styles.css`, located in the `css` folder.
- **A6** File names do not contain uppercase letters, spaces, or transliteration. Names include only English letters and words.
- **A7** The source code is formatted using Prettier.
- **A8** All images and text content are taken from the design mockup.
- **A9** The style normalizer `modern-normalize` is connected.
- **A10** All styles are written in a single file `styles.css`, located in the `css` folder.
- **A11** The code follows the guidelines.

## Markup

- **B1** All icons use vector graphics in SVG format.
- **B2** SVG icons are exported correctly. The “group” option is selected during export, not the individual vector.
- **B3** All icons from the SVG sprite are added to HTML using `<svg>` and `<use>` tags.
- **B4** Icons are added in the Advantages section (the section without a title above Our Team).
- **B5** Social media icons are added in the Our Team section.
- **B7** Social media icons are added in the footer.
- **B8** HTML markup is completed for all elements in the mockup.
- **B9** Tags are used according to their semantic meaning.

## Styling

- **C1** The large image with a dark overlay (under the header) is implemented as a background. A multi-layer background with a gradient is used for the overlay.
- **C2** The background image in the block under the header does not stretch wider than its original size of 1440px.
- **C3** Cards in the Our Team section have a constant shadow effect.
- **C4** Cards in the Our Portfolio section have a shadow effect on hover anywhere on the card.
- **C5** On hover or focus, icons transition to an active state (change color if specified in the design).
- **C6** Transitions are applied to all hover and focus effects (color, background, shadow). Duration: 250ms; timing function: cubic-bezier(0.4, 0, 0.2, 1).
- **C7** Animated properties are explicitly specified in transitions. The value `all` is not used anywhere.
- **C8** In the main navigation, an underline for the current page link is created using the `::after` pseudo-element.
- **C9** The overlay with text on cards in the Our Portfolio section appears on hover anywhere on the card.
- **C10** The blue overlay in the Our Portfolio cards slides up from the bottom.
- **C11** Pseudo-elements do not contain textual content in the `content` property. They are used only for decorative purposes.
