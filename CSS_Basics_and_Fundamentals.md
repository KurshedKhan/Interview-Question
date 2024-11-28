
# CSS Basics and Fundamentals - Interview Preparation

### 1. What is CSS, and why is it used?
CSS (Cascading Style Sheets) is used to style HTML elements by defining their layout, colors, fonts, and more.

### 2. How do you link a CSS file to an HTML document?
Use the `<link>` tag inside the `<head>`:  
```html
<link rel="stylesheet" href="styles.css">
```

### 3. What is the difference between inline, internal, and external CSS?
- **Inline CSS:** Within the `style` attribute of an element.  
- **Internal CSS:** Inside `<style>` tags in the `<head>`.  
- **External CSS:** In a separate file linked via `<link>`.

### 4. What are CSS comments, and how are they used?
CSS comments start with `/*` and end with `*/`. They are used to explain code.  
```css
/* This is a comment */
```

### 5. How do CSS selectors work?
Selectors target HTML elements to apply styles, e.g., `p` selects all `<p>` tags.

### 6. What are CSS units, and what is the difference between relative and absolute units?
- **Absolute units:** Fixed sizes (e.g., `px`, `cm`).
- **Relative units:** Relative to another value (e.g., `em`, `%`).

### 7. How do you center text using CSS?
```css
text-align: center;
```

### 8. What are pseudo-classes, and how are they used in CSS?
Pseudo-classes define the special state of an element, e.g., `:hover` for mouse-over effects.

### 9. How is padding different from margins in CSS?
- **Padding:** Space inside the element's border.  
- **Margin:** Space outside the element's border.

### 10. What is the CSS box model?
The box model includes `content`, `padding`, `border`, and `margin`.

### 11. How do you create rounded corners using CSS?
```css
border-radius: 10px;
```

### 12. What is a pseudo-element, and how is it different from a pseudo-class?
- **Pseudo-element:** Style specific parts of an element (e.g., `::before`).
- **Pseudo-class:** Style element in a specific state (e.g., `:hover`).

### 13. What are web-safe fonts, and why are they important?
Fonts that are universally available across devices to ensure consistent appearance.

### 14. How can you vertically align text within an element?
```css
vertical-align: middle;
``` (for inline or table-cell elements)

### 15. How do you create an unordered list with custom bullet points in CSS?
```css
ul {
  list-style-type: square;
}
```

### 16. What are CSS resets, and why are they used?
CSS resets remove default browser styles for consistency.

### 17. How can you hide elements using CSS?
```css
display: none; /* or */ visibility: hidden;
```

### 18. What is `!important` in CSS, and how does it affect styles?
It overrides other rules, giving the property the highest priority.

### 19. How does the `universal selector (*)` work in CSS?
It selects all elements on the page.
```css
* {
  margin: 0;
}
```

### 20. How do class selectors differ from ID selectors?
- **Class (`.`):** Targets multiple elements.
- **ID (`#`):** Targets a unique element.

### 21. How can you select multiple elements using CSS?
Separate selectors with commas:  
```css
h1, p {
  color: blue;
}
```

### 22. What is a `descendant selector`, and how is it used?
Selects elements inside a specific parent:  
```css
div p { color: red; }
```

### 23. How does the `child selector (>)` differ from the descendant selector?
- **Child selector (`>`):** Targets direct children only.  
- **Descendant selector:** Targets all nested elements.

### 24. What is an `adjacent sibling selector (+)` in CSS?
Selects the next sibling immediately after a specified element:  
```css
h1 + p { color: green; }
```

### 25. How does the `general sibling selector (~)` work in CSS?
Selects all siblings after a specified element:  
```css
h1 ~ p { color: blue; }
```

### 26. How is specificity calculated in CSS?
Based on selectors: Inline styles > IDs > Classes > Elements.

### 27. How do you style links differently for visited and unvisited states?
```css
a:link { color: blue; }
a:visited { color: purple; }
```

# CSS Properties Explained - Interview Preparation

### 1. Background Colors and Images Property
- **background-color:** Sets the background color of an element.  
  Example: `background-color: lightblue;`
- **background-image:** Sets an image as the background.  
  Example: `background-image: url('image.jpg');`

### 2. Font-Family Property
Defines the font used for text.  
Example: `font-family: 'Arial', sans-serif;`

### 3. Text Size Property
- **font-size:** Specifies the size of the text.  
  Example: `font-size: 16px;`

### 4. Text Align Property
Aligns text horizontally within an element.  
Example: `text-align: center;`

### 5. Display Property
Controls the display type of an element.  
Example: `display: block;` or `display: none;`

### 6. Float Property
Floats an element to the left or right.  
Example: `float: left;`

### 7. Z-Index Property
Specifies the stack order of elements.  
Example: `z-index: 10;`

### 8. Borders Property
Defines the border around an element.  
Example: `border: 2px solid black;`

### 9. Margin Property
Sets the space outside the element’s border.  
Example: `margin: 20px;`

### 10. Padding Property
Sets the space inside the element’s border.  
Example: `padding: 10px;`

### 11. Border-Radius Property
Creates rounded corners.  
Example: `border-radius: 10px;`

### 12. Opacity Property
Sets the transparency level of an element.  
Example: `opacity: 0.5;`

### 13. Text Shadows Property
Adds shadow to text.  
Example: `text-shadow: 2px 2px 5px grey;`

### 14. Overflow Property
Controls what happens to content that overflows an element's box.  
Example: `overflow: hidden;`

### 15. Minimum and Maximum Width or Height
- **min-width / min-height:** Sets the minimum size.  
  Example: `min-width: 100px;`
- **max-width / max-height:** Sets the maximum size.  
  Example: `max-width: 500px;`

### 16. Gradient Background Property
Applies gradient backgrounds.  
Example: `background: linear-gradient(to right, red, blue);`

### 17. Outline Property
Sets an outline around an element, outside the border.  
Example: `outline: 2px solid green;`

### 18. Visibility Property
Toggles the visibility of an element without removing it from the layout.  
Example: `visibility: hidden;`

### 19. Line-Height
Controls the height of lines of text.  
Example: `line-height: 1.5;`

### 20. Display Property (Duplicate with #5)
See above.

### 21. Box-Sizing Property
Defines how the total width and height of an element are calculated.  
Example: `box-sizing: border-box;`

### 22. Position Property
Specifies the positioning method for an element.  
Example: `position: absolute;`

### 23. Background Size Property
Specifies the size of the background image.  
Example: `background-size: cover;`

### 24. Clear Property
Clears floats to avoid overlapping.  
Example: `clear: both;`

### 25. Cursor Property
Specifies the type of cursor to display.  
Example: `cursor: pointer;`

### 26. Box-Shadow Property
Adds shadow to an element’s box.  
Example: `box-shadow: 5px 5px 10px grey;`
