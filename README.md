# HTML Course - Lecture 1: Introduction to HTML & Basic Structure

## Objective
- Understand what HTML is and its role in web development.
- Learn the basic structure of an HTML document and essential tags like `<div>`, `<span>`, and more.

---

## What is HTML?

HTML (HyperText Markup Language) is the standard language used to create web pages. It defines the structure of a webpage and is the backbone of web development. It works alongside CSS and JavaScript to design and bring webpages to life.

- **HTML**: Defines the structure of web pages.
- **CSS**: Handles the presentation and styling of the content.
- **JavaScript**: Adds interactivity to web pages.

---

## Basic HTML Document Structure

Below is the basic skeleton of an HTML document:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Webpage</title>
  </head>
  <body>
    <!-- Content will go here -->
  </body>
</html>
```

- **<!DOCTYPE html>**: This declaration defines the document type and version of HTML (HTML5 in this case).
- **<html>**: The root element of the HTML document.
- **<head>**: Contains metadata like title, charset, and linked stylesheets/scripts.
- **<title>**: Defines the title of the document, visible in the browser tab.
- **<body>**: Contains the visible content of the webpage.

## Essential HTML Tags

1. ### Headings

Headings are used to define different levels of headings on a webpage.

```html
<h1>This is a Heading 1</h1>
<h2>This is a Heading 2</h2>
```
- **<h1>**: is the largest heading, <h6> is the smallest.

2. ### Paragraphs

Paragraphs are defined with the <p> tag.

```html
<p>This is a paragraph of text.</p>
```


3. ### Bold and Italics

You can emphasize text using the <strong> and <em> tags.

```html
<strong>This is bold text</strong>
<em>This is italic text</em>
```



4. ### Line Break and Horizontal Rule

To insert a line break or a horizontal rule:

```html
<p>This is a line of text.<br>This is on a new line.</p>
<hr>
```



## Containers: <div> and <span>

**<div>** : Block-level Container

The <div> element is used to group HTML elements together. It acts as a block-level container that helps in organizing content.

```html
<div>
  <h1>My Title</h1>
  <p>This is some text inside a div.</p>
</div>
```


**<span>** : Inline-level Container

The <div> element is used to group HTML elements together. It acts as a block-level container that helps in organizing content.

```html
<p>This is a <span style="color: red;">highlighted</span> word.</p>
```

## Practice Assignment

Create a simple web page with the following elements:

1. Use <div> to structure your content.
2. Include a heading (<h1>), a paragraph (<p>), and some emphasized text (<strong>, <em>).
3. Use <span> to style part of a sentence differently.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Practice Page</title>
</head>
<body>

    <div>
        <h1>Welcome to My Web Page</h1>
        <p>This is a paragraph of text that includes <span style="color: blue;">inline styling</span> using the span tag.</p>
        <strong>This text is bold</strong> and <em>this text is italic</em>.
    </div>

</body>
</html>
```
