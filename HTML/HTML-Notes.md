
HTML —

1. Basic HTML Structure

HTML stands for HyperText Markup Language. It is used to create and structure webpages.

Basic Structure

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>

</body>
</html>

Important Tags

<!DOCTYPE html> — Declares that the document uses HTML5.

<html> — Root element of an HTML document.

<head> — Contains information about the webpage.

<body> — Contains the visible content of the webpage.

<title> — Defines the title displayed in the browser tab.



---

2. Meta Tags

Meta tags provide information about the webpage to the browser.

Character Encoding

<meta charset="UTF-8">

Specifies the character encoding of the webpage.

Viewport

<meta name="viewport" content="width=device-width, initial-scale=1.0">

Helps the webpage display properly on different screen sizes.


---

3. Comments

Comments are used to write notes inside HTML code.

They are not displayed in the browser.

Syntax

<!-- This is a comment -->


---

4. Heading Tags

HTML provides six heading tags:

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

<h1> is the highest-level heading, while <h6> is the lowest-level heading.


---

5. Paragraph Tag

The <p> tag is used to create paragraphs.

Example

<p>This is a paragraph.</p>


---

6. Line Break

The <br> tag is used to insert a line break.

Example

This is line one.<br>
This is line two.


---

7. Image Tag

The <img> tag is used to display an image on a webpage.

Syntax

<img src="image.jpg" alt="Description">

Important Attributes

src — Specifies the image path or URL.

alt — Provides alternative text for the image.

width — Sets the width of the image.

height — Sets the height of the image.


Example

<img src="image.jpg" alt="My Image" width="300" height="200">

Relative Image Path

If the image is inside an images folder:

<img src="images/image.jpg" alt="My Image">


---

8. Bold, Italic and Underline

Bold

The <b> tag makes text bold.

<b>This is bold text</b>

Italic

The <i> tag makes text italic.

<i>This is italic text</i>

Underline

The <u> tag underlines text.

<u>This is underlined text</u>


---

9. Big and Small Text

Big

The <big> tag displays text relatively bigger.

<big>This is big text</big>

Small

The <small> tag displays text relatively smaller.

<small>This is small text</small>


---

10. Horizontal Rule

The <hr> tag creates a horizontal line.

Example

<hr>

It can be used to separate different sections of a webpage.


---

11. Superscript

The <sup> tag displays text above the normal line.

Example

X<sup>2</sup>

Output:

X²


---

12. Subscript

The <sub> tag displays text below the normal line.

Example

H<sub>2</sub>O

Output:

H₂O

It can be used for chemical formulas and similar expressions.


---

13. Preformatted Text

The <pre> tag displays text while preserving spaces and line breaks.

Example

<pre>
I
am
learning
HTML
</pre>

Unlike normal paragraph text, <pre> preserves the formatting of the text.


---

Tags Covered Today

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

Attributes Covered Today

lang
charset
name
content
src
alt
width
height

Today's Learning

HTML → Structure of a Webpage
CSS → Styling
JavaScript → Logic & Interactivity

Day 1 completed: Basic HTML Tags ✅
