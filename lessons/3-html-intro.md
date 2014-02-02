---
layout: post
title: Introduction to HTML
lesson_num: 03
---

<p class="lead">Hypertext Markup Language (HTML) is the basis of every page on the web. HTML provides the meaning and structure to our pages.</p>

## What is HTML?

HTML is a markup language. It tells the web browser what content to display. HTML separates "content" (words, images, audio, video, and so on) from "presentation" (the definition of the type of content and the instructions for how that type of content should be displayed). HTML uses a pre-defined set of elements to identify content types. Elements contain one or more "tags" that contain or express content. Tags are surrounded by angle brackets, and the "closing" tag (the one that indicates the end of the content) is prefixed by a forward slash.

For example, the paragraph element consists of the start tag `<p>` and the closing tag `</p>`. The following example shows a paragraph contained within the HTML paragraph element:

```html
<p>You are beginning to learn HTML.</p>
```

When this content is displayed in a web browser, it looks like this:

You are beginning to learn HTML.

The browser uses the tags as an indicator of how to display the content in the tags.

Elements that contain content can usually also contain other elements. For example, the emphasis element (`<em>`) can be embedded within a paragraph element, to add emphasis to a word or phrase:

```html
<p>You are <em>beginning </em> to learn HTML.</p>
```

When displayed, this looks like:

You are *beginning* to learn HTML.

Some elements do not contain other elements. For example, the image tag ("<img>") specifies the file name of the content (an image) as an attribute:

```html
<img src="smileyface.jpg">
```

"What is HTML" is from Mozilla Developer Networks' [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Introduction)

## Common HTML terms

- **Elements:** Elements define the semantic meaning of their content. Elements include everything between two matching element tags, including the tags themselves. For example, the "<p>" element indicates a paragraph; the "<img>" element indicates an image.
- **Tags:** HTML documents are written in plain text. They can be written in any text editor that allows content to be saved as plain text, such as Notepad, Notepad++, or Sublime,  but most HTML authors prefer to use a specialized editor that highlights syntax and shows the DOM. Tag names may be written in either upper or lower case. However, the W3C (the global consortium that maintains the HTML standard) recommends using lower case.
- **Attributes:** The tag may contain additional information and Such information is called an attribute. Tags such as `<img>` and `<a>` use attributes. Attributes usually consist of 2 parts:
    - An attribute name (such as `src` or `href`)
    - An attribute value (such as `doge.jpg` or `link.html`)
- **Doctype:** In addition to tags, text content, and entities, an HTML document must contain a doctype declaration as the first line. The doctype declaration is not an HTML tag; it is an instruction to the web browser about what version of HTML the page is written in.

Adapted from Mozilla Developer Networks' [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Introduction)

## Creating our first web pages

<iframe src="//slid.es/ascott1/introductiontohtml/embed" width="576" height="420" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

## Common HTML Tags

```html
<p>This is a paragraph</p>

<h1>Heading Level 1</h1>
<h2>Heading Level 2</h2>
<h3>Heading Level 3</h3>
<h4>Heading Level 4</h4>
<h5>Heading Level 5</h5>
<h6>Heading Level 6</h6>

<em>Emphasis, aka italics</em>
<strong>Strong, aka bold</strong>

<ul>
    <li>Unordered list item 1</li>
    <li>Unordered list item 2</li>
    <li>Unordered list item 3</li>
</ul>

<ol>
    <li>Ordered list item 1</li>
    <li>Ordered list item 2</li>
    <li>Ordered list item 3</li>
</ol>

<a href="http://dmd1070.github.io/">This is a link</a>

<img src="pizza.jpg">

<!-- This is a comment. Anything put here will not appear on the page -->
```

For a full list of HTML tags, check out the [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

## Starter HTML Template

A very basic HTML page:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>PAGE TITLE</title> <!-- DON'T FORGET THE TITLE -->
  </head>
  <body>
  <!-- PLACE ALL OF YOUR PAGE CONTENT BELOW HERE -->

  <h1>This is my heading</h1>

  <p>This is a paragraph</p> 

  <!-- AND ABOVE HERE -->
  </body>
</html>
```

**[Our starter HTML template is available to download on Github](https://github.com/DMD1070/html-template).**

## Activity: Menu Markup

Here is the plain text of a pizza menu: [Long Wharf Pizza Menu](/lesson_files/long_wharf_pizza.txt)

To practice our HTML chops, mark it up as a [valid](http://validator.w3.org/) HTML file.