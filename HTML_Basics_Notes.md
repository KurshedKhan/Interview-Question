
# HTML Basics Notes

## 1. `<!DOCTYPE html>` Declaration
Specifies the HTML version to the browser for proper rendering.

## 2. Block vs Inline Elements
- **Block**: Takes up the full width and starts on a new line (e.g., `<div>`, `<p>`).
- **Inline**: Takes up as much space as its content and flows within text (e.g., `<span>`, `<a>`).

## 3. Semantic HTML Tags
Tags like `<header>`, `<article>`, and `<footer>` describe the purpose of the content, improving SEO and accessibility.

## 4. Difference Between `<div>` and `<span>`
- `<div>`: Block-level container for grouping content.
- `<span>`: Inline container for styling parts of text.

## 5. Function of `<meta>` Tag
Provides metadata like character encoding (`charset`), viewport settings (`name="viewport"`), and SEO descriptions.

## 6. Explanation of Tags
- `<html>`: Root of the HTML document.
- `<head>`: Contains metadata like title, styles, and scripts.
- `<title>`: Specifies the browser tab title.
- `<body>`: Contains visible content.

## 7. HTML Comments
`<!-- Comment -->` is used for adding notes that are not displayed in the browser.

## 8. Difference Between `<b>` and `<strong>`
- `<b>`: Adds bold styling without meaning.
- `<strong>`: Adds bold styling with emphasis.

## 9. Creating a Hyperlink
```html
<a href="https://example.com">Link Text</a>
```

## 10. Creating an Ordered List
```html
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
</ol>
```

## 11. Creating an Unordered List
```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

## 12. Opening a Link in a New Tab
```html
<a href="https://example.com" target="_blank">Link Text</a>
```

## 13. Creating a Table
```html
<table>
  <tr>
    <td>Cell 1</td>
    <td>Cell 2</td>
  </tr>
  <tr>
    <td>Cell 3</td>
    <td>Cell 4</td>
  </tr>
</table>
```

## 14. Merging Table Cells
- **Colspan**: `<td colspan="2">Merged</td>` merges columns.
- **Rowspan**: `<td rowspan="2">Merged</td>` merges rows.

## 15. Self-Closing Tags
Tags like `<img>`, `<br>`, and `<hr>` don't require a closing tag.

## 16. Required Attributes for `<img>`
- `src`: Image source URL.
- `alt`: Alternative text for accessibility.

## 17. Line Break
Use `<br>` to insert a line break.

## 18. Horizontal Rule
Use `<hr>` to create a horizontal line.

## 19. Creating a Dropdown List
```html
<select>
  <option value="1">Option 1</option>
  <option value="2">Option 2</option>
</select>
```

## 20. Making a Field Required
Add the `required` attribute: `<input required>`.

## 21. `<fieldset>` and `<legend>`
- `<fieldset>`: Groups related form elements.
- `<legend>`: Provides a caption for the group.

## 22. Purpose of `<label>`
Improves form accessibility:
```html
<label for="name">Name:</label>
<input id="name" type="text">
```

## 23. Password Field
```html
<input type="password">
```

## 24. Placeholder Attribute
```html
<input placeholder="Enter text here">
```

## 25. `<textarea>`
Used for multi-line text input:
```html
<textarea rows="4" cols="50"></textarea>
```

## 26. Checkbox Group
```html
<input type="checkbox" name="opt1"> Option 1
<input type="checkbox" name="opt2"> Option 2
```

## 27. Radio Buttons
```html
<input type="radio" name="group" value="1"> Option 1
<input type="radio" name="group" value="2"> Option 2
```

## 28. Value Attribute
Sets the value of an input: `<input value="default">`.

## 29. `<button>` vs `<input type="button">`
- `<button>`: Allows HTML content inside.
- `<input>`: Simple button, no inner content.

## 30. Action Attribute
Specifies where to submit the form data:
```html
<form action="/submit"></form>
```

## 31. Method Attribute
Defines how to send data:
- `GET`: Appends data to URL.
- `POST`: Sends data in the request body.

## 32. Reset Button
```html
<input type="reset">
```

## 33. Specifying URL in Action
```html
<form action="https://example.com/submit"></form>
```

## 34. Name Attribute
Used to identify form elements during data submission.

## 35. Required Attribute
Ensures a field is filled before submission.

## 36. Date Picker
```html
<input type="date">
```

## 37. `<input type="email">` vs `<input type="text">`
- `email`: Validates email format.
- `text`: Accepts any text.

## 38. `<audio>` vs `<video>`
- `<audio>`: For sound.
- `<video>`: For video content.

## 39. ID vs Class
- `id`: Unique identifier for one element.
- `class`: Can apply styles to multiple elements.

## 40. Global Attributes
Attributes like `id`, `class`, `style` that apply to all elements.

## 41. Title Attribute
Provides a tooltip on hover.

## 42. Style vs Class
- `style`: Inline CSS for one element.
- `class`: Applies shared CSS rules to multiple elements.
