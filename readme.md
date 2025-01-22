<a id="0"></a>

# [HTML 5](#1) | [CSS 3](#2) | [Bootstrap](#3)

Hey there! 
Now that we have finished our Git course, it is time to begin our Frontend journey by learning HTML, CSS and Bootstrap.

##### Dt. 20 Jan, 2025.

<a id="1"></a>

## [HTML 5](#0)

#### What is HTML ?

- HTML - Hyper Text Markup Language
- It constructs the structure of a web page
- Document declaration for HTML5 uses tag ```<!DOCTYPE html>```

#### Structure of HTML Page

- HTML webpage should consists of declaration, html, head, title and body tags.
    ```html
    <html>
        <head>
            <title>Page Title</title>
        </head>
        <body>
            <h1>Hello, World!</h1>
            <p>This is an example paragraph.</p>
        </body>
    </html>
    ```

- ```<html>``` element is the root element of an HTML page
- ```<head>``` element contains meta information about the HTML page
- ```<title>``` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
- ```<body>``` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- ```<h1>``` element defines a large heading
- ```<p>``` element defines a paragraph

#### Elements [*](https://www.w3schools.com/html/html_elements.asp)

  - Define the structure and content
  - Contains Start tag + Content + End tag
      - ```<startTag>Content</endTag>```
  - Empty elements only have start tag (For eg. - ```<br>, <hr>```)
  - Elements can be nested
  - ```<p>This is a paragraph element</p>```

#### Attributes [*](https://www.w3schools.com/html/html_attributes.asp)

  - Provides additional information about HTML Elements
  - All HTML elements can have attributes
  - Specified in start tag
  - Usually in name-value pair
  - ```<a href="www.url.com">Here href is attribute of a(anchor) element</a>```

#### Styling [*](https://www.w3schools.com/html/html_styles.asp)

  - The HTML style attribute is used to add styles to an element, such as color, font, size, and more.
  - ```<tagname style="property:value;">```
  - ```<h1 style="font-family:verdana;">This is inline style</h1>```
  - Styles can be -
      - Inline: ```<tagname style="property:value;">```
      - Internal: ```<style> body {color: blue;} p {color: red;} </style>``` inside head element
      - External: ```<link rel="stylesheet" href="styles.css">``` inside head element

#### Formatting [*](https://www.w3schools.com/html/html_formatting.asp)

  - HTML contains several elements for defining text with a special meaning.
      - `<b>`, `<strong>`, `<i>`, `<em>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, `<sup>`
  - HTML does not preserves the line break and spaces while displaying page, to overcome this use -
      - ```<br>``` - to break a line
      - ```<hr>``` - insert a horizontal line
      - ```<pre>``` - for preformatted text. It preserves line breaks and spaces. Displays text in courier font.

#### Images [*](https://www.w3schools.com/html/html_images.asp)

  - The `<img>` tag is used to embed images in an HTML page.
  - Syntax: `<img src="image.jpg" alt="Description" width="500" height="600">`
  - Attributes:
      - `src`: Specifies the path to the image file.
      - `alt`: Provides alternate text for the image if it cannot be displayed.
      - `width` and `height`: Define the dimensions of the image.

#### Favicon [*](https://www.w3schools.com/html/html_favicon.asp)

  - A favicon is a small icon displayed in the browser tab.
  - It is added using the `<link>` tag in the `<head>` section.
  - Syntax: `<link rel="icon" href="favicon.ico" type="image/x-icon">`

#### Tables [*](https://www.w3schools.com/html/html_tables.asp)

  - Used to display data in a tabular format.
  - Tags -
      - `<table>`: Defines the table.
      - `<tr>`: Table row.
      - `<td>`: Table cell.
      - `<th>`: Table header cell.

#### Lists [*](https://www.w3schools.com/html/html_lists.asp)

  - Ordered List - Displays items in a numbered list.
      - `<ol>`: Defines ordered list.
      - `<li>`: Sets list item.
      - `<ol type="1">`: Sets the type of list item marker. 

  - Unordered List - Displays items with bullets.
      - `<ul>`: Defines unordered list.
      - `<li>`: Sets list item.
      - `<ul style="list-style-type:disc;">`: Sets the type of list item marker.

#### Block Elements [*](https://www.w3schools.com/html/html_blocks.asp)

  - Always start on a new line.
  - Examples: `<div>`, `<p>`, `<h1>`, `<table>`.
  - Example:
      ```html
      <div>
          <p>This is a block element.</p>
      </div>
      ```

#### Inline Elements [*](https://www.w3schools.com/html/html_blocks.asp)

  - Do not start on a new line; they stay inline with other elements.
  - Examples: `<span>`, `<a>`, `<img>`.
  - Example:
      ```html
      <p>This is a <span>span element</span>.</p>
      ```

#### HTML Layout Elements [*](https://www.w3schools.com/html/html_layout.asp)

- Used to structure a webpage's layout.
- Key Elements:
    - `<header>`: Defines a header section.
    - `<nav>`: Defines navigation links.
    - `<section>`: Defines a thematic grouping of content.
    - `<article>`: Defines independent, self-contained content.
    - `<aside>`: Defines content aside from the main content.
    - `<footer>`: Defines a footer for a document or section.


#### Responsiveness [*](https://www.w3schools.com/html/html_responsive.asp)

- Ensures web pages look good on devices of all sizes.
- **Meta Viewport Tag** -
    - Used to control the viewport’s width and scaling.
    - Syntax: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
- **CSS Media Queries** -
    - Used to apply styles based on screen size.
    - Example:
        ```css
        @media (max-width: 600px) {
            body {
                background-color: lightblue;
            }
        }
        ```

#### HTML Semantics [*](https://www.w3schools.com/html/html5_semantic_elements.asp)

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

#### Entities [*](https://www.w3schools.com/html/html_entities.asp) & Symbols [*](https://www.w3schools.com/html/html_symbols.asp)

- HTML entities are used to display special characters.
- Examples:
    - `<`: `&lt;`
    - `>`: `&gt;`
    - `©`: `&copy;`

##### Dt. 21 Jan, 2025.

#### HTML Forms [*](https://www.w3schools.com/html/html_forms.asp)

- What are HTML Forms?
  - Forms are used to collect user input and send it to a server.
  - The `<form>` tag is used to create an HTML form.
  - Syntax:
    ```html
    <form action="submit.php" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <input type="submit" value="Submit">
    </form>
    ```
  - Attributes of `<form>`:
    - `action`: Specifies the server endpoint for form submission.
    - `method`: Specifies the HTTP method (`GET` or `POST`).

- Form Elements -
  - `<input>`: Defines an input field.
    - Types: `text`, `password`, `checkbox`, `radio`, `file`, etc.
  - `<textarea>`: Defines a multi-line text input.
  - `<select>`: Creates a dropdown list.

  - `<button>`: Defines a clickable button.

#### HTML Graphics [*](https://www.w3schools.com/html/html5_canvas.asp)

- What are HTML Graphics?
  - HTML provides elements to create and display graphics in web pages.

- Canvas -
  - The `<canvas>`  element is used to draw graphics, on the fly, via JavaScript.
  - Well suited for graphic-intensive games

- SVG (Scalable Vector Graphics) - 
  - The `<svg>` element is used to define vector-based graphics.
  - SVG graphics are scalable, and do not lose any quality if they are zoomed or resized.

#### HTML Media [*](https://www.w3schools.com/html/html_media.asp)

- What is HTML Media?
  - HTML allows embedding audio and video in web pages using `<audio>` and `<video>` tags.

- Audio -
  - The `<audio>` tag is used to embed audio files.
  - Three supported video formats: MP3, WAV, and OGG.

- Video - 
  - The `<video>` tag is used to embed video files.
  - Three supported video formats: MP4, WebM, and Ogg.

- Attributes - 
  - `controls`: Adds play, pause, and volume controls.
  - `autoplay`: Automatically plays the media.
  - `loop`: Plays the media in a loop.
  - `muted`: Mutes the media by default.

#### Cross Browser HTML - Polyfill and Fallback [*](https://www.geeksforgeeks.org/what-is-a-polyfill/)

- What is Cross Browser Compatibility?
  - Ensuring that web pages work consistently across different browsers (e.g., Chrome, Firefox, Safari, Edge).

- Challenges - 
  - Browsers interpret HTML, CSS, and JavaScript differently.
  - Older browsers may not support modern web features.

- Techniques for Cross Browser Compatibility**:
  - Polyfills - 
    - JavaScript code that provides modern functionality in older browsers.
    - Use - When a modern feature is critical and must work exactly as intended (e.g., JavaScript features).
    
  - CSS Fallbacks - 
    - Provide alternative styles for browsers that don't support modern CSS features.
    - Use - When graceful degradation is acceptable, often for styling or UI features (e.g., CSS or animations).

  - Graceful Degradation - 
    - Ensure the website functions properly with reduced functionality in older browsers.

  - Feature Detection - 
    - Use `@supports` for CSS or feature detection libraries like Modernizr for JavaScript.

##### With this we have finished our HTML course. Quite extensive, wasn't it? But it covers almost everything that's there in HTML. So it was worth it!

##### For Quick Reference/ Visualization of [HTML.](https://htmlreference.io/)

<a id="2"></a>

## [CSS 3](#0)

#### Introduction to CSS [*](https://www.w3schools.com/css/css_intro.asp)

- What is CSS?
  - CSS (Cascading Style Sheets) is used to style and format HTML content.
  - It controls the layout, design, colors, fonts, and overall appearance of web pages.
  - CSS can be added in three ways -
    - **Inline**: Directly within an HTML element using the `style` attribute.
    - **Internal**: Inside a `<style>` tag within the `<head>` section of the document.
    - **External**: By linking an external CSS file using a `<link>` tag.
  - Cascading Order - 
    - All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, in order -
        1. Inline style (inside an HTML element)
        2. External and internal style sheets (in the head section)
        3. Browser default


- Advantages of CSS - 
  - Separates content (HTML) from presentation (CSS).
  - Makes websites easier to maintain and update.
  - Allows for consistent styling across multiple pages.

#### CSS Selectors [*](https://www.w3schools.com/css/css_selectors.asp)

- What are CSS Selectors?
  - Selectors are patterns used to target HTML elements for styling.
  - Categories of Selector:
    - **Simple selectors** - select elements based on name, id, class
    - **Combinator selectors** - select elements based on a specific relationship between them
    - **Pseudo-class selectors** - select elements based on a certain state
    - **Pseudo-elements selectors** - select and style a part of an element
    - **Attribute selectors** - select elements based on an attribute or attribute value
  - Simple Selectors:
    - **Universal Selector (`*`)**: Targets all elements.
    - **Element Selector (`element`)**: Targets all instances of a specific element.
    - **Class Selector (`.class`)**: Targets elements with a specific class.
    - **ID Selector (`#id`)**: Targets an element with a specific ID.
  - To group selectors, separate each selector with a comma.

- Examples - 
  - `h1 { color: blue; }` – Targets all `<h1>` elements.
  - `.btn { background-color: red; }` – Targets elements with class `btn`.

#### Backgrounds [*](https://www.w3schools.com/css/css_background.asp) & Borders [*](https://www.w3schools.com/css/css_border.asp)

- CSS allows customization of element backgrounds and borders:
  - Backgrounds - 
    - Add color, images, or gradients.
    - Properties: `background-color`, `background-image`, `background-size`, `background-repeat`, `background-attachment`, `background-position`, etc.
    - Alternatively, we can use shorthand property - `background`

  - Borders - 
    - Customize edges of elements.
    - Properties: `border-width`, `border-style`, `border-color`, `border-radius`.

- Applications - 
  - Highlight sections with attractive backgrounds.
  - Create distinct visual boundaries with borders.

#### CSS Margins [*](https://www.w3schools.com/css/css_margin.asp) & Padding [*](https://www.w3schools.com/css/css_padding.asp)

- What are Margins and Padding?
  - Margins: Space outside an element, separating it from other elements.
  - Padding: Space between the element’s content and its border.

- Key Properties - 
  - `margin`: Controls margin on all sides.
  - `margin-top`, `margin-right`, `margin-bottom`, `margin-left`: Control margins on specific sides.
  - `margin: auto;`: centers the element horizontally within its container.
  - Similarly, `padding` has shorthand and individual side properties.

#### Sizing [*](https://www.w3schools.com/css/css_dimension.asp) & The Box Model [*](https://www.w3schools.com/css/css_boxmodel.asp)

- What is the Box Model?
  - The box model defines the space an element occupies:
    - `Content`: The main content of the element (using width and height).
    - `Padding`: Space around the content.
    - `Border`: A boundary surrounding the padding.
    - `Margin`: Space outside the border.

- Sizing - 
  - Set the size of elements using `width`, `height`, `max-width`, `max-height`, etc.
  - Use units like `px`, `%`, `em`, `rem`, or `vw`.

#### Text Formatting [*](https://www.w3schools.com/css/css_text.asp) & Fonts [*](https://www.w3schools.com/css/css_font.asp)

- CSS allows styling of text with properties like:
  - Text Properties - 
    - `color`, `text-align`, `text-decoration`, `line-height`, etc.
  - Font Properties - 
    - `font-family`, `font-size`, `font-style`, `font-weight`, etc.

- Custom Fonts - 
  - Use `@font-face` to include custom fonts or link Google Fonts for additional font styles.

#### Styling Anchors [*](https://www.w3schools.com/css/css_link.asp) & Lists [*](https://www.w3schools.com/css/css_list.asp)

- Anchors (`<a>`) - 
  - Customize links using pseudo-classes like `:hover`, `:visited`, `:active`.
  - Example: Change color on hover.

- Lists (`<ul>` and `<ol>`) - 
  - Style bullets or numbers using `list-style-type` or `list-style-image`.

#### CSS Layout [*](https://www.w3schools.com/css/css_display_visibility.asp)

- Key Properties for Layout - 
  - `display`: Controls the element's layout model (e.g., `block`, `inline`, `flex`).
  - `position`: Specifies the positioning (`static`, `relative`, `absolute`, `fixed`).
  - `z-index`: Controls stacking order.
  - `overflow`: Defines how content is handled when it exceeds its container.

#### CSS Combinators [*](https://www.w3schools.com/css/css_combinators.asp)

- What are CSS Combinators?
  - Combinators define relationships between elements:
    - **Descendant (` `)**: Targets children at any depth.
    - **Child (`>`):** Targets direct children.
    - **Adjacent Sibling (`+`)**: Targets the next sibling.
    - **General Sibling (`~`)**: Targets all siblings after a specific element.

#### Pseudo-classes [*](https://www.w3schools.com/css/css_pseudo_classes.asp)

  - Define the state of an element.
  - Example: `:hover`, `:focus`, `:nth-child()`.
  
#### Pseudo-elements [*](https://www.w3schools.com/css/css_pseudo_elements.asp)

  - Style specific parts of elements.
  - Example: `::before`, `::after`.

#### CSS Attribute Selectors [*](https://www.w3schools.com/css/css_attribute_selectors.asp)

- Target elements based on attributes:
  - `[attr]`: Matches elements with the attribute.
  - `[attr="value"]`: Matches elements with the exact attribute value.
  - Various other selectors are `[attr~="value"]`, `[attr|="value"]`, `[attr^="value"]`, `[attr$="value"]`, `[attr*="value"]`.

#### CSS Forms [*](https://www.w3schools.com/css/css_form.asp)

- Style form elements like `input`, `textarea`, `select`.
- Common Properties:
  - `border`, `background`, `padding`, `width`, `height`.

#### CSS Box Sizing [*](https://www.w3schools.com/css/css3_box-sizing.asp)

- What is Box Sizing?
  - Defines how the total width and height of an element are calculated.
  - Values:
    - `content-box`: Default. Width includes only content.
    - `border-box`: Width includes content, padding, and border.

#### Gradients [*](https://www.w3schools.com/css/css3_gradients.asp) & Shadows [*](https://www.w3schools.com/css/css3_shadows.asp)

- Gradients - 
  - Linear and radial gradients using `background-image`.

- Shadows - 
  - `box-shadow`: Adds shadow to boxes.
  - `text-shadow`: Adds shadow to text.

#### CSS Media Queries [*](https://www.w3schools.com/css/css3_mediaqueries.asp)

- Enable responsive design by applying styles based on device properties:
  - Example:
    ```css
    @media (max-width: 600px) {
        body {
            background-color: lightblue;
        }
    }
    ```
- For media queries - 
    - **not**: This keyword inverts the meaning of an entire media query.
    - **only**: This keyword prevents older browsers that do not support media queries from applying the specified styles. It has no effect on modern browsers.
    - **and**: This keyword combines a media type and one or more media features.

#### CSS Flexbox [*](https://www.w3schools.com/css/css3_flexbox.asp)

- What is Flexbox?
  - A layout model for creating responsive and flexible designs.
  - Key Properties:
    - `display: flex;`
    - `justify-content`, `align-items`, `flex-wrap`.

#### CSS Grid [*](https://www.w3schools.com/css/css_grid.asp)

- What is CSS Grid?
  - A powerful layout system for creating complex designs.
  - Define rows and columns using `grid-template-rows` and `grid-template-columns`.
  - Difference in Grid and Flexbox -
    - The CSS Grid Layout should be used for two-dimensional layout, with rows AND columns.
    - The CSS Flexbox Layout should be used for one-dimensional layout, with rows OR columns.

#### Debugging Styling in the Browser

- Use browser developer tools to:
  - Inspect elements.
  - View applied styles.
  - Debug layout issues using tools like "Box Model" visualization.

Okay then. Let's call it a day now. We've finished most of the CSS. Will give a finishing touch to this course tomorrow. Keep it up!

##### Dt. 22 Jan, 2025.

Let's cover some videos on CSS today to clear our concepts even more.

#### Important Topics Video Links 

- CSS Selector - [Video](https://www.youtube.com/watch?v=l1mER1bV0N0) & [Cheat-Sheet](/CSS-Selector-Cheat-Sheet%20.pdf)
- CSS Psuedo-Elements - [Video](https://www.youtube.com/watch?v=OtBpgtqrjyo) & [Blog](https://blog.webdevsimplified.com/2021-12/css-pseudo-elements/)
- CSS Positioning - [Video](https://www.youtube.com/watch?v=jx5jmI0UlXU) & [Blog](https://blog.webdevsimplified.com/2022-01/css-position/)
- CSS Box Model - [Video](hhttps://www.youtube.com/watch?v=rIO5326FgPE) & [Blog](https://blog.webdevsimplified.com/2021-12/box-model/)
- CSS Units - [Video](https://www.youtube.com/watch?v=N5wpD9Ov_To)

##### With this we come to an end for our CSS module. Next we'll jump on to Frontend Framework - Bootstrap.

##### For Quick Reference/ Visualization of [CSS.](https://cssreference.io/)

<a id="3"></a>

## [Bootstrap](#0)

#### Getting Started [*](https://getbootstrap.com/docs/5.0/getting-started/introduction/)

- What is Bootstrap?
  - Bootstrap is a popular open-source front-end framework for building responsive and mobile-first websites.
  - It includes HTML, CSS, and JavaScript-based design templates for typography, forms, buttons, tables, navigation, modals, and more.

- How to Include Bootstrap?
  - Via CDN -  Use Bootstrap’s CSS and JavaScript files directly from a Content Delivery Network.
    ```html
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"></script>
    ```
  - Using NPM - Install Bootstrap locally via Node Package Manager.
    ```bash
    npm install bootstrap
    ```
  - Download Source Files - Download Bootstrap's source files and include them in your project.

- Why Use Bootstrap?
  - Offers prebuilt components and a responsive grid system.
  - Simplifies cross-browser compatibility.
  - Highly customizable with variables and Sass.

#### Layout [*](https://getbootstrap.com/docs/5.0/layout/breakpoints/)

- Breakpoints - 
  - Breakpoints are customizable widths that determine how your responsive layout behaves across device or viewport sizes in Bootstrap.
  - Bootstrap includes six default breakpoints - X-small, `sm`, `md`, `lg`, `xl`, and `xxl`.

- Containers - 
  - Containers are a fundamental building block of Bootstrap that contain, pad, and align your content within a given device or viewport.

- Responsive Grid System - 
  - Based on a 12-column layout and uses flexbox for responsiveness.
  - Use classes like `.container`, `.row`, and `.col` to define layouts.
  - Columns are responsive and adjust based on the screen size:
    - `.col-sm`, `.col-md`, `.col-lg`, `.col-xl`, `.col-xxl`.

- Columns - 
  - Columns build on the grid’s flexbox architecture. Flexbox means we have options for changing individual columns and modifying groups of columns at the row level. 

- Gutters - 
  - Gutters are the padding between your columns, used to responsively space and align content in the Bootstrap grid system.

- Utilities for Spacing and Alignment - 
  - Use utility classes like `m-3` (margin) or `p-2` (padding).
  - Alignment classes like `d-flex`, `justify-content-center`, and `align-items-center`.

#### Content [*](https://getbootstrap.com/docs/5.0/content/reboot/)

- Typography - 
  - Predefined styles for headings, paragraphs, blockquotes, and more.
  - Classes like `.display-1` for large headings or `.lead` for emphasized text.

- Images - 
  - Responsive images using `.img-fluid` to scale images with the screen size.
  - Add classes like `.rounded`, `.rounded-circle`, or `.img-thumbnail` for styling.

- Tables - 
  - Create styled tables with `.table`.
  - Enhance tables with additional classes like `.table-striped`, `.table-bordered`, or `.table-hover`.

- Figures - 
  - Use the `<figure>` and `<figcaption>` elements with Bootstrap's `.figure` class to add captions to images.

#### Forms [*](https://getbootstrap.com/docs/5.0/content/reboot/)

- Form Controls - 
  - Customize input fields, text areas, and dropdowns using classes like `.form-control` and `.form-select`.

- Layout Options - 
  - Use `.form-group` and `.row` for organizing form elements.
  - Inline forms with `.form-inline`.

- Validation - 
  - Built-in validation states with classes like `is-valid` and `is-invalid`.

- Checkboxes and Radios - 
  - Style checkboxes and radio buttons with `.form-check`.

- File Input - 
  - Add custom file input fields using `.form-control`.

#### Components [*](https://getbootstrap.com/docs/5.0/components/accordion/)

- Buttons - 
  - Use `.btn` along with variants like `.btn-primary`, `.btn-secondary`, and more.
  - Buttons can be styled as block-level, outline, or disabled.

- Navbar - 
  - Create responsive navigation bars using `.navbar` and its related classes.
  - Include togglers for mobile views with `.navbar-toggler`.

- Modals - 
  - Add modal dialogs for alerts, confirmations, or forms using `.modal`.

- Cards - 
  - Use `.card` for creating containers with headers, footers, and content.

- Alerts - 
  - Show contextual feedback with `.alert` classes like `.alert-success`, `.alert-danger`, etc.

- Utilities - 
  - Bootstrap offers various utility classes for colors, spacing, borders, and more.

#### FCC Bootstrap Course

To get deeper understanding of this framework, I went through this [Bootstrap](https://www.youtube.com/watch?v=-qfEOE4vtxE) course on FreeCodeCamp.

##### With this we have successfully completed learning Bootstrap Framework.

##### Refer [this](https://getbootstrap.com/docs/5.0/getting-started/introduction/) for Documentation of Bootstrap.

## LMS HTML/CSS Course

Now that I have gone through the whole HTML & CSS course, it is time for me to put my skills to test. Good luck to me!

I have created navigation bar of our page. Will complete the rest of the page tomorrow and let's call it a day today.