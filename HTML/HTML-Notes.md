# HTML — Day 1 Notes

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
