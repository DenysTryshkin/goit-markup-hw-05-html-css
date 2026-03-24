## Acceptance Criteria for Mentor Review

### Project

* **A1** All styles are written in a single file `styles.css`, located in the `css` folder.
* **A2** Source code is formatted using Prettier.
* **A3** All images and text content are taken from the design mockup.
* **A4** The modern-normalize stylesheet is included.
* **A5** Code follows the project guidelines.

### Modal Window

* **B1** Markup and styling for the backdrop (dark semi-transparent background) are implemented.
* **B2** The backdrop covers 100% of the viewport height and width and is fixed.
* **B3** Markup and styling for the modal window are implemented.
* **B4** The modal window is centered both vertically and horizontally within the backdrop.
* **B5** A close button is implemented and styled in the top-right corner of the modal.
* **B6** The modal window and backdrop are hidden by default.
* **B7** Adding the `is-open` class to the backdrop makes both the backdrop and modal visible.

### Forms

* **C1** HTML markup for all design elements is implemented.
* **C2** Tags are used according to their semantic meaning.
* **C3** The newsletter subscription form and all its elements are implemented in the footer.
* **C4** The request form and all its elements are implemented in the modal window.
* **C5** All input elements have a `name` attribute.
* **C6** The `name` attribute values are descriptive and clearly define the purpose of each field.
* **C7** All inputs have associated `<label>` elements.
* **C8** Inputs include a `placeholder` attribute where specified in the design.
* **C9** Submit buttons have `type="submit"`.
* **C10** All new icons used in forms are added to the SVG sprite `icons.svg`.

### Styling

* **D1** Styling for the newsletter subscription form in the footer is implemented.
* **D2** Styling for the request form in the modal window is implemented.
* **D3** On input focus, the border and icon color change according to the design.
* **D4** The default checkbox for accepting the license agreement is hidden.
* **D5** The custom checkbox is styled manually using an SVG checkmark from the sprite.
* **D6** All hover and focus effects (color, background, shadow) include transitions with duration 250ms and timing function `cubic-bezier(0.4, 0, 0.2, 1)`.

