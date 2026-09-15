# HTML - Day 1 Notes

HTML stands for HyperText Markup Language. It is used to create and structure webpages.

## 1. Basic HTML Structure

Basic structure of an HTML document:

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

### Important Tags

<!DOCTYPE html> : Declares that the document uses HTML5.

<html> : The root element of the HTML document.

<head> : Contains information and metadata about the webpage.

<body> : Contains the content that is visible in the browser.

<title> : Sets the title of the webpage, which appears in the browser tab.


## 2. Meta Tags

### Character Encoding

<meta charset="UTF-8">

Specifies UTF-8 character encoding, which supports a wide range of characters from different languages.

### Viewport

<meta name="viewport" content="width=device-width, initial-scale=1.0">

Ensures that the webpage scales correctly on different devices such as mobile phones, tablets and computers.


## 3. Comments in HTML

Comments are used to write notes in HTML code. They are not displayed in the browser.

<!-- This is an HTML comment -->


## 4. Heading Tags

HTML provides six heading tags:

<h1>This is a heading</h1>
<h2>This is a heading</h2>
<h3>This is a heading</h3>
<h4>This is a heading</h4>
<h5>This is a heading</h5>
<h6>This is a heading</h6>

<h1> is the highest-level heading.
<h6> is the lowest-level heading.

Headings are used to organize content.


## 5. Paragraph Tag

The <p> tag is used to create a paragraph.

<p>This is a paragraph.</p>

Paragraphs are used to group related sentences together and create readable content.


## 6. Line Break - <br>

The <br> tag is used to create a line break.

Example:

This is line one.<br>
This is line two.


## 7. Image Tag - <img>

The <img> tag is used to display images.

<img src="image.jpg" alt="Description">

### Attributes of Image Tag

src : Specifies the path or URL of the image.

alt : Provides alternative text for the image.

Example:

<img src="image.jpg" alt="Description">

If the image is inside another folder:

<img src="images/image.jpg" alt="Description">

We can also set the width and height:

<img src="image.jpg" alt="Description" width="200" height="200">


## 8. Bold, Italic and Underline

### Bold

<b>This text is bold</b>

### Italic

<i>This text is italic</i>

### Underline

<u>This text is underlined</u>


## 9. Big and Small Tags

### Big

The <big> tag is used to make text relatively bigger.

<big>This text is big</big>

### Small

The <small> tag is used to make text relatively smaller.

<small>This text is small</small>


## 10. Horizontal Rule - <hr>

The <hr> tag is used to create a horizontal line.

<hr>

It can be used to separate content.


## 11. Superscript - <sup>

The <sup> tag is used to display text above the normal baseline.

Example:

X<sup>2</sup>

Output:

X²


## 12. Subscript - <sub>

The <sub> tag is used to display text below the normal baseline.

Example:

H<sub>2</sub>O

Output:

H₂O

It can be used for chemical formulas.

Example:

<p>H<sub>2</sub>O</p>


## 13. Preformatted Text - <pre>

The <pre> tag is used to display preformatted text.

It preserves spaces, line breaks and whitespace.

Example:

<pre>
I
am
learning
HTML
</pre>

Normal HTML generally ignores extra spaces and line breaks, while <pre> preserves them.


# Tags Covered Today

<!DOCTYPE html>
<html>
<head>
<meta>
<title>
<body>

<h1>
<h2>
<h3>
<h4>
<h5>
<h6>

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


# Attributes Covered Today

lang
charset
name
content
src
alt
width
height


# Key Learning

HTML is used to create and structure webpages.

HTML = Structure
CSS = Styling
JavaScript = Logic and Interactivity

Learn → Practice → Build → Commit → Push
