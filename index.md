# HTML
# 1. What is meta tag and detailed explained?
- The ```<meta> tag``` in HTML is used to provide metadata about the HTML document.
- **Metadata** is information about the webpage.
- It is **not visible** directly to users but helps **browsers**, **search engines**, and other services understand the content and behavior of the webpage.
- The `<meta> tag` is placed within the `<head> tag` section of the HTML document.<br><br>
### Here are some common uses and **attributes** of the `<meta> tag`.
#### a. Character Set Declaration (charset)
- **Usage**: Specifies the character encoding for the document.
- `<meta charset="UTF-8">`
- **Explanation**: The most common encoding, UTF-8, supports a wide range of characters, including various languages and symbols. This ensures the browser displays text correctly.
#### b. Viewport Settings (viewport)
- **Usage**: Controls the layout on mobile devices and responsive design.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
- **Explanation**:
- >width=device-width sets the width of the page to follow the screen’s width.
- >initial-scale=1.0 sets the initial zoom level when the page is loaded.
- >It helps ensure that the site looks good on both desktop and mobile devices.
#### c. Description (description)
- **Usage**: Provides a brief summary of the page content, often used by search engines.
- `<meta name="description" content="This is a detailed guide on HTML meta tags.">`
- **Explanation**: 
- > This description is displayed in search engine results. 
- > A well-written description can help improve the click-through rate by providing users with a relevant summary.

#### d. Keywords (keywords)
- **Usage**: Specifies relevant keywords for search engines.
- `<meta name="keywords" content="HTML, meta tag, web development, SEO">`
- **Explanation**: 
- > Keywords give search engines hints about the content of the page. 
- > However, modern search engines, like Google, give less importance to this tag for ranking.