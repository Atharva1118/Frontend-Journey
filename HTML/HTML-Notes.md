

HTML stands for **HyperText Markup Language**. It is used to create and structure webpages.

---

## 1. Basic HTML Structure

HTML provides the basic structure of a webpage.

### Syntax

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>...</title>
</head>
<body>
    ...
</body>
</html>
```

### Important Tags

- `<!DOCTYPE html>` — Declares HTML5.
- `<html>` — Root element.
- `<head>` — Contains information about the webpage.
- `<body>` — Contains visible webpage content.
- `<title>` — Defines the browser tab title.

---

## 2. Meta Tags

Meta tags provide information about the webpage.

### Character Encoding

**Syntax:**

`<meta charset="UTF-8">`

### Viewport

**Syntax:**

`<meta name="viewport" content="width=device-width, initial-scale=1.0">`

---

## 3. Comments

Comments are notes written inside HTML code. They are not displayed in the browser.

### Syntax

`<!-- ... -->`

---

## 4. Heading Tags

HTML provides six heading levels.

### Syntax

`<h1>...</h1>`

`<h2>...</h2>`

`<h3>...</h3>`

`<h4>...</h4>`

`<h5>...</h5>`

`<h6>...</h6>`

`<h1>` is the highest-level heading and `<h6>` is the lowest-level heading.

---

## 5. Paragraph Tag

The `<p>` tag is used to create paragraphs.

### Syntax

`<p>...</p>`

---

## 6. Line Break

The `<br>` tag is used to insert a line break.

### Syntax

`<br>`

---

## 7. Image Tag

The `<img>` tag is used to display images.

### Syntax

`<img src="..." alt="...">`

### Attributes

- `src` — Specifies the image path or URL.
- `alt` — Provides alternative text for the image.
- `width` — Sets the width of the image.
- `height` — Sets the height of the image.

### Syntax with Width and Height

`<img src="..." alt="..." width="..." height="...">`

---

## 8. Bold, Italic and Underline

### Bold

The `<b>` tag is used to make text bold.

**Syntax:**

`<b>...</b>`

### Italic

The `<i>` tag is used to make text italic.

**Syntax:**

`<i>...</i>`

### Underline

The `<u>` tag is used to underline text.

**Syntax:**

`<u>...</u>`

---

## 9. Big and Small Text

### Big

The `<big>` tag is used to display relatively bigger text.

**Syntax:**

`<big>...</big>`

### Small

The `<small>` tag is used to display relatively smaller text.

**Syntax:**

`<small>...</small>`

---

## 10. Horizontal Rule

The `<hr>` tag creates a horizontal line.

### Syntax

`<hr>`

---

## 11. Superscript

The `<sup>` tag displays text above the normal line.

### Syntax

`<sup>...</sup>`

---

## 12. Subscript

The `<sub>` tag displays text below the normal line.

### Syntax

`<sub>...</sub>`

---

## 13. Preformatted Text

The `<pre>` tag preserves spaces and line breaks in the text.

### Syntax

`<pre>...</pre>`

---

# Tags Covered Today

```text
<!DOCTYPE html>
<html>
<head>
<meta>
<title>
<body>

<h1> to <h6>

<p>
<br>
<img>
<b>
<i>
<u>
<big>
<small>
<hr>
<sup>
<sub>
<pre>
```

# Attributes Covered Today

```text
lang
charset
name
content
src
alt
width
height
```

---

## Semantic HTML

Semantic HTML tags clearly describe the purpose of the content they contain.

### Semantic Tags

| Tag | Purpose |
|---|---|
| `<header>` | Defines the header section of a webpage. |
| `<main>` | Defines the main content of a webpage. |
| `<section>` | Groups related content together. |
| `<article>` | Defines self-contained content that can be independently distributed or reused. |
| `<aside>` | Defines supplementary content related to the main content, such as sidebars or advertisements. |
| `<footer>` | Defines the footer section of a webpage. |
| `<nav>` | Used to contain navigational links. |

### Basic Structure

```html
<header>
    ...
</header>

<main>
    <section>
        <article>
            ...
        </article>
    </section>

    <aside>
        ...
    </aside>
</main>

<footer>
    ...
</footer>


## Opening Links

The `<a>` tag is used to create hyperlinks.

### Target Attribute

The `target` attribute specifies where to open the linked page.

| Value | Purpose |
|---|---|
| `_self` | Opens the link in the same tab. |
| `_blank` | Opens the link in a new tab. |

### Syntax

```html
<a href="https://www.google.com" target="_self">Google</a>

<a href="https://www.google.com" target="_blank">Google</a>
```

## File Download Using HTML

The `<a>` tag can be used to create a file download link.


### Syntax

```html
<a href="filename.exe">Download File</a>
```



## Div and Span Tags

### Div Tag

The `<div>` tag is a block-level container element used to group HTML elements.

- It does not have semantic meaning on its own.
- It is commonly used for styling and layout.
- It starts on a new line.
- It takes the full available width of its parent by default.
- It can contain block-level elements, inline elements, and other `<div>` elements.
- It is commonly used with CSS and JavaScript.

### Syntax

```html
<div>
    Content goes here
</div>
```

### Span Tag

The `<span>` tag is an inline element used to group or style small parts of content.

- It does not start on a new line.
- It takes only the required width.
- It is commonly used with CSS and JavaScript.
- It can be used inside paragraphs or other elements.

### Syntax

```html
<span>
    Content goes here
</span>
```

### Difference Between Div and Span

| Feature | `<div>` | `<span>` |
|---|---|---|
| Type | Block-level element | Inline element |
| New line | Starts on a new line | Does not start on a new line |
| Width | Takes available width by default | Takes required width |
| Usage | Groups larger sections of content | Groups small parts of content |
| Layout | Used for structure and layout | Used for inline content and styling |

### Important Points

- Block-level elements generally start on a new line.
- Inline elements generally remain on the same line.
- `<div>` and `<span>` do not have semantic meaning by themselves.


## Image as a Link

An image can be made clickable by placing the `<img>` tag inside the `<a>` tag.

### Syntax

```html
<a href="https://example.com">
    <img src="image.jpg" alt="Image">
</a>
```

## Website Links

The `<a>` tag is used to create hyperlinks to other webpages.

### Syntax

```html
<a href="https://www.google.com" target="_blank">
    Google
</a>
```

### Important Points

- `href` specifies the destination URL.
- `target="_blank"` opens the link in a new tab.
- `<br>` creates a line break between links.
- An image can be used as a clickable link.


## Lists in HTML

Lists are used to organize and group related items in HTML.

### Types of Lists

HTML provides three main types of lists:

1. Ordered List
2. Unordered List
3. Definition List

### 1. Ordered List (`<ol>`)

- Used when the order of items matters.
- Items are numbered automatically.
- `<li>` defines each list item.

**Syntax:**

```html
<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ol>
```

**Type Attribute:**

The `type` attribute changes the numbering style.

| Type | Description |
|---|---|
| `1` | Numbers (default) |
| `A` | Uppercase letters |
| `a` | Lowercase letters |
| `I` | Uppercase Roman numerals |
| `i` | Lowercase Roman numerals |

**Example:**

```html
<ol type="A">
    <li>First item</li>
    <li>Second item</li>
</ol>
```

### 2. Unordered List (`<ul>`)

- Used when the order of items does not matter.
- Items are displayed with bullet points.
- `<li>` defines each list item.

**Syntax:**

```html
<ul>
    <li>Milk</li>
    <li>Bread</li>
    <li>Eggs</li>
</ul>
```

**Type Attribute:**

The `type` attribute changes the bullet style.

| Type | Description |
|---|---|
| `disc` | Filled circle |
| `circle` | Hollow circle |
| `square` | Square |

**Example:**

```html
<ul type="square">
    <li>Milk</li>
    <li>Bread</li>
</ul>
```

### 3. Definition List (`<dl>`)

- Used to define terms and their descriptions.
- `<dl>` defines the description list.
- `<dt>` defines the term.
- `<dd>` defines the description.

**Syntax:**

```html
<dl>
    <dt>HTML</dt>
    <dd>Hypertext Markup Language</dd>

    <dt>CSS</dt>
    <dd>Cascading Style Sheets</dd>
</dl>
```

### Practice

Created `lists.html` to practice:

- Ordered List
- Unordered List
- Definition List



## Tables in HTML

Tables are used to display data in a structured format using rows and columns.

### Basic Table Tags

| Tag | Description |
|---|---|
| `<table>` | Defines the table |
| `<tr>` | Defines a table row |
| `<th>` | Defines a table header cell |
| `<td>` | Defines a table data cell |
| `<thead>` | Defines the table header section |
| `<tbody>` | Defines the table body section |

### Basic Table Example

```html
<table>
    <tr>
        <th>Name</th>
        <th>Role</th>
    </tr>

    <tr>
        <td>Harry</td>
        <td>Developer</td>
    </tr>
</table>
```

### Table Attributes

| Attribute | Description |
|---|---|
| `border` | Specifies the table border width |
| `cellpadding` | Space between cell content and border |
| `cellspacing` | Space between table cells |
| `width` | Specifies table width |
| `height` | Specifies table height |
| `align` | Specifies table alignment |
| `bgcolor` | Specifies background color |

**Note:** These are traditional HTML table attributes. CSS is commonly used for modern table styling.

### Colspan

The `colspan` attribute merges multiple columns into one cell.

**Example:**

```html
<tr>
    <td colspan="2">Merged Cell</td>
</tr>
```

### Rowspan

The `rowspan` attribute merges multiple rows into one cell.

**Example:**

```html
<tr>
    <td rowspan="2">Merged Cell</td>
    <td>Data 1</td>
</tr>
```

### Practice

Created `tables.html` to practice:

- Basic HTML tables
- Table header and body
- Colspan
- AI-generated CSS styling


## Forms in HTML

Forms allow users to enter data and interact with websites.

### Common Form Elements

| Tag | Description |
|---|---|
| `<form>` | Container for form elements |
| `<input>` | Creates input fields |
| `<label>` | Defines a label for an input |
| `<textarea>` | Creates a multi-line text field |
| `<select>` | Creates a dropdown list |
| `<option>` | Defines an option in a dropdown |
| `<button>` | Creates a clickable button |

### Form Attributes

| Attribute | Description |
|---|---|
| `action` | Specifies where form data is sent |
| `method` | Specifies the HTTP method, such as GET or POST |
| `for` | Associates a label with an element's `id` |
| `type` | Specifies the input or button type |
| `name` | Identifies form data |
| `placeholder` | Displays a hint inside an input |
| `required` | Makes a field mandatory |
| `id` | Provides a unique identifier |
| `value` | Specifies the input's value |

### Common Input Types

- `text` — Single-line text
- `tel` — Telephone number
- `email` — Email address
- `password` — Masked password input
- `number` — Numeric input
- `date` — Date selection
- `radio` — Select one option from a group
- `checkbox` — Select one or more options

### Example

```html
<form action="/submit" method="POST">
    <label for="name">Name:</label>
    <input type="text" id="name" name="username" required>

    <button type="submit">Submit</button>
</form>
```

### Practice

Created `forms.html` to practice HTML form elements and input types.

**Note:** CSS in the practice file is AI-generated and will be studied separately.
