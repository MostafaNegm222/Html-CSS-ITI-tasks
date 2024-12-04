# README: CSS Table, Navbar, and Template Tasks

This document outlines the solutions and design details for the given CSS tasks, which include creating a styled table, designing a responsive navbar, and implementing a CSS template.

---

## Task 1: Table Design

### Description
- Create a table styled with CSS as shown in the provided image.

### Key Features
1. **Table Structure**:
   - Use `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>` elements to structure the table.
2. **Styling**:
   - **Borders**: Use `border` and `border-collapse: collapse` to create seamless table borders.
   - **Colors**: Apply `background-color` for table headers and alternating row colors.
   - **Alignment**: Use `text-align` and `vertical-align` for proper alignment.
   - **Padding**: Add `padding` to table cells for better spacing.

### Additional Notes
- Ensure the table is responsive by using `width: 100%` and media queries if needed.
- The design closely follows the provided image.

---

## Task 2: Navbar Design

### Description
- Create a responsive navigation bar with a list of links, styled using CSS.

### Key Features
1. **HTML Structure**:
   - Use `<ul>` for the list and `<li>` for each navigation item.
   - Inside each `<li>`, include an `<a>` tag for links.

2. **Styling**:
   - **List Style**: Remove default bullets using `list-style-type: none`.
   - **Alignment**: Use `display: inline-block` for `<li>` items to align them horizontally.
   - **Mouseover Effect**: Change the background color of items on `:hover`.
   - **Fixed Position**: Set `position: fixed` for the navbar to keep it visible during scroll.
   - **Sticky Position**: Optionally use `position: sticky` to allow the navbar to scroll with the page until it reaches the top.

3. **Content Below Navbar**:
   - Add content such as a paragraph below the navbar.
   - Use `padding` or `margin` to push down the content to avoid overlap with the fixed navbar.

4. **Difference Between `display` Values**:
   - **inline**: The element flows in line with text but doesn’t respect height and width.
   - **block**: The element takes up the full width and starts on a new line.
   - **inline-block**: Combines features of `inline` and `block`, allowing height and width to be set while flowing in line with text.

### References
- [CSS Inline vs Inline-block](https://www.w3schools.com/css/css_inline-block.asp)
- [Alligator CSS Guide](https://alligator.io/css/display-inline-vs-inline-block/)

---

## Task 3: CSS Template

### Description
- Create a CSS-based template inspired by the [Webuni template](https://preview.colorlib.com/#webuni).

### Key Features
1. **Container**:
   - Use a single container for the layout to maintain consistency.
   - Apply responsive design using `flex` or `grid` properties.

2. **Layout Design**:
   - Use `grid-template-areas` or `flexbox` to structure the layout.
   - Ensure proper alignment and spacing for all components.

3. **Responsive Design**:
   - Apply media queries to ensure the layout is visually appealing on all screen sizes.

4. **Styling**:
   - Use consistent colors, padding, and font styles across all elements.
   - Keep the design modern and professional, similar to the Webuni template.

---

## How to Run

1. **HTML and CSS Setup**:
   - Save the HTML structure in an `.html` file.
   - Link the CSS file using `<link rel="stylesheet" href="style.css">`.

2. **Browser View**:
   - Open the HTML file in a browser to view the styled table, navbar, and template.

3. **Customization**:
   - Modify the styles in `style.css` to adjust colors, padding, and other design elements.

---

## Additional Notes

- **Cross-Browser Compatibility**: Use appropriate prefixes for CSS properties to ensure compatibility.
- **Responsiveness**: Test the design on various screen sizes and devices.
- **Validation**: Ensure the HTML and CSS code is valid using online validators.

Enjoy building and customizing your designs! 😊
