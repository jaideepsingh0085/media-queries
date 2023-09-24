# media-queries
![Screenshot 2023-09-24 221323](https://github.com/jaideepsingh0085/media-queries/assets/128147644/d464d731-70a1-4128-9e12-bf16ac1b2513)
![Screenshot 2023-09-24 221334](https://github.com/jaideepsingh0085/media-queries/assets/128147644/363dceee-0a30-4313-ba81-7cab49dd131f)
![Screenshot 2023-09-24 221342](https://github.com/jaideepsingh0085/media-queries/assets/128147644/85fc3747-7c7c-40d2-8e18-eaa491eee089)
![Screenshot 2023-09-24 221350](https://github.com/jaideepsingh0085/media-queries/assets/128147644/15853ff5-3695-4ad2-8f52-6cc63f1be153)
![Screenshot 2023-09-24 221355](https://github.com/jaideepsingh0085/media-queries/assets/128147644/61a0189f-1f70-43c3-9db6-93bebff365f9)

Hosted Link : https://jaideepsingh0085.github.io/media-queries/

HTML :
<!DOCTYPE html>: Declares the document type and version of HTML being used.
<html lang="en">: Defines the HTML document and specifies the language as English.
<head>: Contains metadata about the HTML document.
<meta charset="UTF-8">: Sets the character encoding to UTF-8 for proper text rendering.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design.
<title>: Sets the title of the web page displayed in the browser tab.
<link href="./style.css" rel="stylesheet">: Links an external CSS file called "style.css" for styling.
<body>: Contains the visible content of the web page.
<img src="..." alt="..." class="image">: Embeds an image with source, alt text, and a class for styling.
<main class="main">: Defines the main content section of the page with a class attribute for styling.
<h1>: Specifies a level 1 heading for the main title.
<p>: Represents paragraphs of text within the main content.
<br />: Inserts line breaks to create vertical spacing within paragraphs.
<span>: Defines an inline element to apply styling to a specific portion of text.
<button>: Creates a button element that 

CSS :
*: Selects all elements on the page and applies the following properties.

margin: Sets the margin to zero for all elements.

box-sizing: Sets the box model to "border-box" for all elements.

font-family: Specifies the default font as "Roboto" and a fallback font as "sans-serif."

body: Styles the overall appearance of the web page, setting height, width, background, grid layout, and other properties.

height: Sets the height of the body to 100% of the viewport height (100vh).

width: Specifies the width of the body to 90% and limits it to a maximum of 1200px.

display: Uses a grid layout with specific areas and content placement properties.

grid-template-areas: Defines grid areas for layout, separating "image" and "main" content.

place-content: Centers the content both horizontally and vertically.

align-items: Aligns items in the center along the block axis.

background: Applies a linear gradient background with multiple color stops.

gap: Sets the gap between elements within the grid layout.

.image: Styles the image with specific grid area placement and width.

.main: Styles the main content area with centered text alignment.

h1: Styles level 1 headings, adjusting font size, margin, and line height.

p: Styles paragraphs, setting font family, weight, size, and line height.

span: Adds a bottom border to spans within paragraphs.

button: Styles buttons with background color, text color, font family, and other properties.

Media Query for Tablet Screen: Adjusts styling for screens with widths between 601px and 900px, modifying background, image width, and heading size.

Media Query for Mobile Screen: Modifies styles for screens with widths between 0px and 600px, changing grid layout, background, image dimensions, and font sizes for responsive design.
