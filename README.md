# Top 40 HTML Interview Questions

## 1. What is HTML and how is it different from XHTML?

**HTML** stands for Hypertext Markup Language and is used to define the structure of web content. XHTML stands for Extensible Hypertext Markup Language and is a stricter, more XML-based version of HTML.

The most important differences between HTML and XHTML are:

- **Syntax:** XHTML is stricter than HTML and adheres to XML rules and regulations.
- **Mandatory tags:** In XHTML, the `<!DOCTYPE>` declaration, the `xmlns` attribute in `<html>`, and the `<html>`, `<head>`, `<title>`, and `<body>` tags are mandatory.
- **Element structure:** Elements must always be properly nested and closed in XHTML.
- **Case sensitivity:** In XHTML, element names and attribute names must always be in lowercase.
- **Attribute values:** In XHTML, attribute values must always be quoted.

## 2. Explain the purpose of the `<!DOCTYPE>` declaration in HTML.

The `<!DOCTYPE>` declaration is an instruction to the web browser about what version of HTML the page is written in. It is the first line of code required in every HTML or XHTML document. It is not an HTML tag.

## 3. Differentiate between inline and block-level elements in HTML.

In HTML, elements are classified into two categories: block-level elements and in-line elements.

**Block-level elements** always start a new line and take up the full width available. They are used to create larger sections of content and layout structuring.

Some examples of block-level elements are:

`<p>`, `<form>`, `<ul>`, `<ol>`, `<li>`, `<table>`, `<header>`, `<footer>`, `<nav>`, `<section>`, `<article>`, and `<aside>`.

**Inline elements** do not start on a new line and only take up as much width as necessary. They are used to apply specific styles or add interactive elements to content.

Some examples of inline elements are:

`<a>`, `<abbr>`, `<acronym>`, `<b>`, `<em>`, `<i>`, `<img>` and `<kbd>`.

## 4. Describe the use of the `<meta>` tag and its attributes.

The `<meta>` tag is an HTML element that provides metadata about an HTML document. Metadata is data (information) about data. The <meta> tag has the following attributes and uses:

- **charset:** Specifies the character encoding for the HTML document, such as `UTF-8`.
- **name:** Specifies a name for the metadata such as description, keywords, author, or viewport.
- **content:** Specifies the value associated with the name or http-equiv attribute.
- **http-equiv:** Provides an HTTP header for the information/value of the content attribute, such as content-type, default-style, or refresh.

## 5. What is purpose of the `<head>` and `<body>` tags in an HTML document.

### `<head>` Tag

The `<head>` element contains machine-readable information about the document like its **title** , **scripts,** and **style sheets.**

The metadata contained within the `<head>` tag is not displayed on the page but is used by browsers, search engines, and other web services to control the page’s dimensions, scaling, keywords, description, author, and other properties.

### `<body>` Tag

The `<body>` tag is the last child of the `<html>` tag. It is used to contain the actual content of the page. It holds everything from the heading, and paragraphs to the unique `div` containers inside the `<body>` tag.

## 6. Explain the importance of the `alt` attribute in the `<img>` tag.

The `alt` attribute is important in the `<img>` tag in HTML. It provides alternative text an image if the image cannot be displayed, or if the user is using a screen reader. The alt text should describe the content of the image and its function on the page.

The alt attribute is also important for **search engine optimization (SEO).** Search engines use the alt text to understand the content of the image to index it properly. This can help improve the visibility of the page in search results.

## 7. How does the `<a>` tag contribute to creating hyperlinks in HTML?

The `<a>` tag, also known as the anchor tag, is the essential tag for creating hyperlinks in HTML. It works by:

1. **Marking the linkable content:** You enclose the text or element you want to make clickable within the opening and closing `<a>` tags.
2. **Specifying the destination:** The `href` attribute is used to define the target URL or resource the link will lead to. This can be an external web page, a file, an email, an address, or even a specific section within the same document.
3. **Controlling link behavior (optional):** The `target` attribute can be used to specify where the linked resource should open, such as in a new window or tab (`_blank`) or within the current window (`_self` by default).

## 8. Describe the difference between `<div>` and `<span>` tags.

`<div>` and `<span>` are two commonly used tags that are used to group related parts of a web page.

`<div>` is a block-level element, starting a new line and taking up the full width, while `<span>` is an inline element, flowing smoothly with surrounding content.

## 9. Explain the concept of semantic HTML and provide examples.

Semantic HTML is a way of writing HTML that emphasizes the meaning of content rather than its presentation. It uses HTML tags to describe the content of a web page in a way that is meaningful to both humans and machines.

Some examples of semantic HTML tags are:

- `<header>`: Defines a header for a document or section.
- `<nav>`: Defines a set of navigation links.
- `<main>`: Defines the main content of a document.
- `<article>`: Defines an independent, self-contained piece of content.
- `<section>`: Defines a section of a document.
- `<aside>`: Defines content that is tangentially related to the content around it.
- `<footer>`: Defines a footer for a document or section.

Using semantic HTML can help improve the accessibility, search engine optimization, and maintainability of a web page. It can also make the code easier to read and understand for developers.

## 10. What is the purpose of the `<form>` tag in HTML?

The `<form>` tag is used to create an HTML form for user input. The `<form>` element can contain one or more of the following form elements: `<input>`, `<textarea>`, `<button>`, `<select>`, `<option>`, `<optgroup>`, `<fieldset>`, `<label>`, and `<output>`.

The `<form>` tag is used to collect user input, such as text, numbers, and selections, and send it to a server for processing. The `<form>` tag has several attributes, such as **action**, **method**, and **enctype**, that determine how the form data is sent and processed.

## 11. How can you include comments in HTML?

To include comments in HTML, use the following syntax:

```html
<!-- This is a comment -->
```

The `<!--` and `-->` tags are used to enclose the comment text. Comments are not displayed in the browser, but they can help document your HTML code.

## 12. What is the significance of the `<table>` element in HTML?

The `<table>` element is used to create an HTML table, which is a way of displaying data in rows and columns. Tables are commonly used to display data such as financial reports, sports scores, and product comparisons.

The `<table>` element contains one or more `<tr>` elements, which define the rows of the table. Each `<tr>` element contains one or more `<td>` elements, which define the cells of the table. The `<th>` element is used to define the header cells in the table.

## 13. Explain the difference between the `<script>` tag with the `async` and `defer` attributes.

The `<script>` tag is used to include JavaScript code in an HTML document. The `async` and `defer` attributes are used to control how the browser downloads and executes the JavaScript code.

The `async` attribute tells the browser to download the script asynchronously as soon as it is encountered in the HTML code. The script is executed as soon as it is downloaded, even if the HTML document has not finished parsing. This can improve the performance of the page, but it can also lead to unpredictable behavior if the script depends on each other.

## 14. How can you embed audio and video in HTML using native elements?

Audio and video can be embedded using `<audio>` and `<video>` elements in HTML.

The `<audio>` element is used to embed audio files to a web page, and the `<video>` element is used to embed a video. The `<audio>` and `<video>` elements can be controlled with HTML or JavaScript and styled with CSS.

## 15. Describe the role of the `<nav>` element in HTML5.

The `<nav>` element is a semantic HTML5 tag that is used to define a section of a webpage specifically designed for navigation. It is used to group navigation links, such as the site menus or table of contents.

The `<nav>` element is intended only for major blocks of navigation links. Browsers, such as screen readers for disabled users, can use this element to determine whether to omit the initial rendering of this content.

## 16. What is the purpose of the `<aside>` tag in HTML?

The `<aside>` tag is a semantic HTML5 tag that is used to define a section of a webpage specifically designed for content that is related to the primary content of the webpage but does not constitute the main intent of the primary page. It is used to group content such as author information, links, related content, and so on.

The `<aside>` tag is intended only for content that is indirectly related to the main content of the page. Browsers, such as screen readers for disabled users, can use this element to determine whether to omit the initial rendering of this content.

## 17. Explain the concept of HTML entities and provide examples.

**HTML entities** are special codes that are used to represent characters that cannot be typed directly on a keyboard or that have special meaning in HTML. They are used to display reserved HTML characters, such as the less than sign (<), greater than sign (>), and ampersand (&), and to display characters that are not present in the character set used in the page.

HTML entities are represented by an ampersand (&), followed by a name or number, and then a semicolon (;).

Some examples of HTML entities:

- **`&lt;`**: Less than sign (<)
- **`&gt;`**: Greater than sign (>)
- **`&amp;`**: Ampersand (&)
- **`&quot;`**: Double quotation mark (”)
- **`&cent;`**: Cent sign (¢)
- **`&pound;`**: Pound sign (£)
- **`&yen;`**: Yen sign (¥)
- **`&euro;`**: Euro sign (€)
- **`&copy;`**: Copyright symbol (©)
- **`&reg;`**: Registered trademark symbol (®)

## 18. How can you create ordered and unordered lists in HTML?

To create an ordered list, use `<ol>` tag. Each item in the list is defined using `<li>` tag. Here’s an example of how to create an ordered list.

```html
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```

To create an unordered list, use the `<ul>` tag. Each item in the list is defined using the `<li>` tag. Example to create an unordered list.

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

In both cases, you can add additional attributes to the **`<ul>`** or **`<ol>`** tags to change the appearance of the list, such as the type of bullet points or numbering used.

## 19. What is the purpose of the `<header>` and `<footer>` tag in HTML5?

The `<header>` and `<footer>` tags are semantic HTML5 tags. They are used to define the header and footer sections of a web page.

The `<header>` tag is used to define the header section of a web page, which contains the site title, logo, navigation menu, and other introductory content. The `<header>` tag can also be used to define the header section of an article, section, or other part of a web page.

The `<footer>` tag is used to define the footer section of a web page, which typically contains the copyright information, contact details, and other concluding content. The `<footer>` tag can also be used to define the footer section of an article, section, or other part of a web page.

## 20. Describe the use of the `<abbr>` and `<cite>` tags.

The `<abbr>` tag is used to define an abbreviation or an acronym in HTML. It is used to provide useful information to browsers, translation systems, and search engines. The `<abbr>` tag has a `title` attribute that can be used to provide a full description of the abbreviation or acronym.

The `<cite>` tag is used to define the title of a work, such as a book, a movie, or a song. It is used to provide useful information to browsers, translation systems, and search engines. The `<cite>` tag has no specific attributes.

## 21. How do you create a hyperlink that opens in a new tab or window?

To create a hyperlink that opens in a new tab or window, use the **`target`** attribute in the **`<a>`** tag. The `target` attribute specifies where to open the linked document. To open the linked document in a new tab or window, set the value of the `target` attribute to `"_blank"`.

Here’s an example”:

```html
<a href="https://www.example.com" target="_blank">Link text</a>
```

## 22. Explain the difference between the `<strong>` and `<b>` tags.

The `<strong>` and `<b>` tags are both used to make the text bold in HTML. However, they have different semantic meanings.

The `<b>` tag is used to apply a bold style text to text, without indicating that the text is more important or has greater significance than other text on the page. The `<b>` tag is a presentational tag and should not be used to convey meaning.

The `<strong>` tag, on the other hand, is used to indicate that the text is of greater importance than other text on the page. The `<strong>` tag is semantic and should be used to convey meaning.

## 23. Describe the role of `<figure>` and `<figcaption>` elements.

The `<figure>` element is used to identify a perceivable section of content that typically contains a graphical document, images, code snippets, or example text. The `<figcaption>` element is used to provide a caption or a description of the content within the `<figure>` element.

## 24. How can you create a responsive design in HTML?

The following techniques can be used to create responsive design in HTML:

1. **Viewport meta tag:** Add the `<meta>` tag to all your web pages to set the viewport of your page, which will give the browser instructions on how to control the page’s dimensions and scaling.
2. **Use media queries:** Use media queries to apply different styles to your web page based on the size of the screen.
3. **Flexible images:** Use the max-width property to make images flexible and scale down if necessary.
4. **Flexible grids:** Use flexible grids to create a layout that adapts to different screen sizes.

## 25. Explain the use of the `<detail>` and `<summary>` tags.

The `<detail>` and `<summary>` tags are HTML5 tags that are used to create an interactive widget that the user can open or close. The `<detail>` tag is used to define a section of content that is initially hidden but could be displayed if the user wishes to see it. The `<summary>` tag is used to provide a title or header for the details section.

The `<details>` and `<summary>` tags can be used to create collapsible sections of content, such as FAQs, help sections, or long descriptions.

## 26. What is the purpose of the `<main>` tag in HTML5?

The `<main>` tag is a semantic HTML5 tag that is used to define the main content of a web page. It is used to identify the primary content of a document or application, and should not contain any content that is repeated across documents such as sidebars, navigation, links, copyright information, site logos, and search forms.

The `<main>` tag is intended to be used only once per page, and should not be a descendant of an `<article>`, `<footer>`, `<header>`, or `<nav>` element.

## 27. How can you embed external CSS styles in an HTML document?

To embed external CSS styles in an HTML document, you can use the `<link>` tag inside the `<head>` section of the HTML document. The `<link>` tag has two required attributes: `rel` and `href`. The `rel` attribute specifies the relationship between the document and the linked file, and `href` attribute specifies the location of the linked file.

Example code:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Web Page</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>Welcome to my web page!</h1>
    <p>This is some text on my web page.</p>
  </body>
</html>
```

## 28. Explain the concept of HTML5 `data` attributes.

HTML5 data attributes are a way to store custom data in HTML elements. They allow developers to add extra information to an HTML element without using non-standard attributes or extra properties on the DOM.

Data attributes are defined using the `data-*` attribute syntax, where `*` is a custom name for the attribute.

Example code:

```html
<div data-color="red">This is a red box.</div>
```

## 29. How do you create a dropdown list in HTML?

To create a dropdown list in HTML, you can use the `<select>` tag. the `<select>` tag creates a dropdown list, and the `<option>` tag is used to define the available options in the list.

Example code:

```html
<select>
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="mercedes">Mercedes</option>
  <option value="audi">Audi</option>
</select>
```

## 30. Describe the purpose of the `<canvas>` element in HTML5.

The `<canvas>` element is an HTML6 element that is used to draw graphics on a webpage using JavaScript. The `<canvas>` element provides a rectangular area on a web page where you can draw graphics, such as lines, circles, text, and images.

The `<canvas>` element is only a container for graphics, and you must use JavaScript to draw the graphics. The `<canvas>` element has several methods for drawing paths, boxes, circles, text, and adding images.

## 31. Explain the difference between `GET` and `POST` methods in HTML forms.

The `GET` and `POST` methods are used to send data from a client to a server. The main difference between the two methods is that the `GET` method sends the data in the URL of the request, while the `POST` method sends the data in the body of the request.

## 32. How can you disable a form element using HTML?

You can disable a form element using the `disabled` attribute in HTML. The `disabled` attribute is a Boolean attribute that can be added to any form element, such as input, select, and textarea. When present, it specifies that the form element should be disabled and cannot be used by the user.

## 33. Describe the purpose of the `<progress>` and `<meter>` elements.

The `<progress>` and `<meter>` elements are two new HTML5 elements that can be used to display scalar measurements or fractional values.

The `<progress>` element is used to convey how much work in a task has been completed, such as a file upload or a quiz progress.

The `<meter>` element is used to display a measurement on a known scale, such as disk usage or temperature.

## 34. How do you set the background image in HTML?

You can set a background image in HTML using the **`background-image`** property in CSS.

Example code:

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      body {
        background-image: url("path/to/image.jpg");
        background-repeat: no-repeat;
        background-size: cover;
      }
    </style>
  </head>
  <body>
    <!-- Your HTML content here -->
  </body>
</html>
```

## 35. Explain the role of the `<iframe>` tag and its attributes.

The `<iframe>` tag in HTML stands for inline frame and is used to embed another HTML document within the current document within the current document. It is a container element that allows you to display content from another source on your web page.

## 36. What is the purpose of the `colspan` and `rowspan` attributes in a table?

The `colspan` and `rowspan` attributes in HTML tables are used to merge or span cells across **columns** and **rows.** These attributes allow you to create more complex and visually appealing tables.

The `colspan` attribute is used to make a cell span over multiple columns. It specifies the number of columns that the cell should span. For example, if a cell has a **colspan** of 2 it will span over two columns.

The `rowspan` attribute is used to make a cell span over multiple rows. It specifies the number of rows that the cell should span. For example, if a cell has a **rowspan** of 2, it will span over two rows.

## 37. How can you create a horizontal line in HTML?

You can create a horizontal line in HTML using the **`<hr>`** tag. The **`<hr>`** tag is an empty element that creates a horizontal line across the page.

## 38. Describe the use of the `<datalist>` element in HTML forms.

The **`<datalist>`** element in HTML is used to provide an autocomplete feature for **`<input>`** elements. It specifies a list of pre-defined options for the input element which users can select as they input data. The `<datalist>` element’s `id` attribute must be equal to the `<input>` element’s `list` attribute to bind them together.

## 39. Explain the role of the `<blockquote>` and `<q>` tags.

The `<blockquote>` and `<q>` tags are used to provide semantic markup for quotations. The main difference between them is that `<blockquote>` is used for longer quotations that span multiple paragraphs, while `<q>` is used for shorter quotations that are part of a paragraph.

## 40. How can you create a responsive image in HTML?

A responsive image automatically adjusts its size to fit the screen size of the device it is being viewed on. To create a responsive image, set the `max-width` of the image to `100%`, and the `height` to `auto`.

**Example code:**

```css
img {
  max-width: 100%;
  height: auto;
}
```
