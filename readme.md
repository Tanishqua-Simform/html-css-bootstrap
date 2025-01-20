# HTML 5 | CSS | Bootstrap

Hey there! 
Now that we have finished our Git course, it is time to begin our Frontend journey by learning HTML, CSS and Bootstrap.

##### Dt. 20 Jan, 2025.

## HTML 5

##### What is HTML ?

- HTML - Hyper Text Markup Language
- It constructs the structure of a web page
- Document declaration for HTML5 uses tag ```<!DOCTYPE html>```

---

##### Structure of HTML Page

- HTML webpage should consists of declaration, html, head, title and body tags.

<!DOCTYPE html>
    <html>
        <head>
            <title>Page Title</title>
        </head>
        <body>
            <h1>Hello, World!</h1>
            <p>This is an example paragraph.</p>
        </body>
    </html>

- ```<html>``` element is the root element of an HTML page
- ```<head>``` element contains meta information about the HTML page
- ```<title>``` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
- ```<body>``` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- ```<h1>``` element defines a large heading
- ```<p>``` element defines a paragraph

---

##### Elements and Attributes

- **Elements**
    - Define the structure and content
    - Contains Start tag + Content + End tag
        - ```<startTag>Content</endTag>```
    - Empty elements only have start tag (For eg. - ```<br>, <hr>```)
    - Elements can be nested
    - ```<p>This is a paragraph element</p>```
- **Attributes**
    - Provides additional information about HTML Elements
    - All HTML elements can have attributes
    - Specified in start tag
    - Usually in name-value pair
    - ```<a href="www.url.com">Here href is attribute of a(anchor) element</a>```

---

##### Styling and Formatting

- **Styles**
    - The HTML style attribute is used to add styles to an element, such as color, font, size, and more.
    - ```<tagname style="property:value;">```
    - ```<h1 style="font-family:verdana;">This is inline style</h1>```
    - Styles can be -
        - Inline: ```<tagname style="property:value;">```
        - Internal: ```<style> body {color: blue;} p {color: red;} </style>``` inside head element
        - External: ```<link rel="stylesheet" href="styles.css">``` inside head element
- **Formatting**
    - HTML contains several elements for defining text with a special meaning.
        - ```<b>``` - Bold text
        - ```<strong>``` - Important text
        - ```<i>``` - Italic text
        - ```<em>``` - Emphasized text
        - ```<mark>``` - Marked text
        - ```<small>``` - Smaller text
        - ```<del>``` - Deleted text
        - ```<ins>``` - Inserted text
        - ```<sub>``` - Subscript text
        - ```<sup>``` - Superscript text
    - HTML does not preserves the line break and spaces while displaying page, to overcome this use -
        - ```<br>``` - to break a line
        - ```<hr>``` - insert a horizontal line
        - ```<pre>``` - for preformatted text. It preserves line breaks and spaces. Displays text in courier font.

---

##### Images and Favicon

- **Images**:
    - The `<img>` tag is used to embed images in an HTML page.
    - Syntax: `<img src="image.jpg" alt="Description" width="500" height="600">`
    - Attributes:
        - `src`: Specifies the path to the image file.
        - `alt`: Provides alternate text for the image if it cannot be displayed.
        - `width` and `height`: Define the dimensions of the image.

- **Favicon**:
    - A favicon is a small icon displayed in the browser tab.
    - It is added using the `<link>` tag in the `<head>` section.
    - Syntax: `<link rel="icon" href="favicon.ico" type="image/x-icon">`

---

##### Tables and Lists

- **Tables**:
    - Used to display data in a tabular format.
    - Tags:
        - `<table>`: Defines the table.
        - `<tr>`: Table row.
        - `<td>`: Table cell.
        - `<th>`: Table header cell.
    - Example:
        ```html
        <table>
            <tr>
                <th>Name</th>
                <th>Age</th>
            </tr>
            <tr>
                <td>John</td>
                <td>30</td>
            </tr>
        </table>
        ```

- **Lists**:
    - Ordered List (`<ol>`): Displays items in a numbered list.
        ```html
        <ol>
            <li>Item 1</li>
            <li>Item 2</li>
        </ol>
        ```
    - Unordered List (`<ul>`): Displays items with bullets.
        ```html
        <ul>
            <li>Item 1</li>
            <li>Item 2</li>
        </ul>
        ```

---

##### Block and Inline Elements

- **Block Elements**:
    - Always start on a new line.
    - Examples: `<div>`, `<p>`, `<h1>`, `<table>`.
    - Example:
        ```html
        <div>
            <p>This is a block element.</p>
        </div>
        ```

- **Inline Elements**:
    - Do not start on a new line; they stay inline with other elements.
    - Examples: `<span>`, `<a>`, `<img>`.
    - Example:
        ```html
        <p>This is a <span>span element</span>.</p>
        ```

---

##### HTML Layout Elements

- Used to structure a webpage's layout.
- Key Elements:
    - `<header>`: Defines a header section.
    - `<nav>`: Defines navigation links.
    - `<section>`: Defines a thematic grouping of content.
    - `<article>`: Defines independent, self-contained content.
    - `<aside>`: Defines content aside from the main content.
    - `<footer>`: Defines a footer for a document or section.
- Example:
    ```html
    <header>
        <h1>Website Title</h1>
    </header>
    <nav>
        <a href="#">Home</a> | <a href="#">About</a>
    </nav>
    <section>
        <article>
            <h2>Article Title</h2>
            <p>Article content here.</p>
        </article>
    </section>
    <footer>
        <p>Copyright © 2025</p>
    </footer>
    ```

---

##### Responsiveness

- Ensures web pages look good on devices of all sizes.
- **Meta Viewport Tag**:
    - Used to control the viewport’s width and scaling.
    - Syntax: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
- **CSS Media Queries**:
    - Used to apply styles based on screen size.
    - Example:
        ```css
        @media (max-width: 600px) {
            body {
                background-color: lightblue;
            }
        }
        ```

---

##### HTML Semantics

- Semantic elements clearly define the purpose of the content.
- Examples:
    - `<header>`: Header section.
    - `<footer>`: Footer section.
    - `<article>`: Independent content.
    - `<section>`: Thematic grouping of content.
    - `<nav>`: Navigation links.
- Benefits:
    - Improves code readability.
    - Enhances accessibility for screen readers.
    - Better SEO performance.

---

##### Entities and Symbols

- HTML entities are used to display special characters.
- Examples:
    - `<`: `&lt;`
    - `>`: `&gt;`
    - `©`: `&copy;`
    - `&`: `&amp;`
    - `★`: `&#9733;`
- Example usage:
    ```html
    <p>Use &lt; and &gt; to display < and > in HTML.</p>
    ```

---