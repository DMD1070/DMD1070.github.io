---
layout: post
title: Intermediate HTML & CSS
lesson_num: 05
---

<p class="lead">Now that we know the basics of HTML and CSS, let's level up by introducing new tags and ways to style things.</p>

## Intermediate HTML

Together we'll be marking up and styling the [Husky Cupcakes menu](/lesson_files/husky_cupcakes_menu.txt).

### `<span>` and `<div>`

The `span` and `div` tags are generic containers for content on our page. `div`'s are used to represent **blocks** of content, while `span`'s are used to represent **inline** content.

```html
<div>
  <p>Any kind of content <span>here</span>.</p>
</div>
```

### tables

Tables are used to represent tabular data. Here's an example of a simple table:

```html
<table>
  <tr>
    <td>John</td>
    <td>Doe</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Doe</td>
  </tr>
</table>
```

Here's a table with header cells:

```html
<table>
  <tr>
    <th>First Name</th>
    <th>Last Name</th>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Doe</td>
  </tr>
</table>
```

### classes and ID's

We can apply classs and ID's to our HTML. This allows us to give greater meaning to our document and more easily add styles or behaviors to specific elements.

```html
<h1 id="site-title">This heading has an id of 'site-title'</h1>

<p class="intro">This paragraph has a class of 'intro'</p>
```

So, what's the difference? IDs can only be used **once** per valid HTML page, while we may apply classes to as many elements as we like.


## Intermediate CSS

### Borders

We can give things borders:

```css
p {
  border-width: 1px;
  border-style: solid;
  border-color: #1fa67a;
}
```

Though I find it much easier to use the shorthand version:

```css
p {
  border: 1px solid #1fa67a
}
```

Possible border styles are: *dotted, dashed, solid, double, groove, ridge, inset, and outset.*

### Getting more specific (classes, IDs, and nested selectors)

By using classes, IDs, and nested selectors make it much easier to style specific elements on a page.

```css
/* this will style any element with the intro class*/
.intro {
  color: #1fa67a;
  font-size: 18px;
}

/* this will style any element with the title id */
#title {
  font-weight: bold;
}

/* this will only style span tags within a paragraph */
p span {
  color: blue;
}

/* this will only style paragraphs inside of an element with the .intro class */
.intro p {
  font-style: italic;
}

```

### Link styles

By default links are blue and visited links are purple. We can style links as follows:

```css
/* style the default link color */
a:link {
  color: #52736B
}

/* style visited links */
a:visited {
  color: #093844;
}

/* style hover/focus links /*
a:hover,
a:active,
a:focus {
  color: #D94214;
}
```

### Center your page

Though we'll talk about layout in more depth in an upcoming class, a common request has been to center your page content on the screen. Here's how we would do that:

The HTML:

```html
<!-- HTML <head></head> above this -->
<body>
  <div class="wrap">
    <!-- PAGE CONTENT HERE -->
  </div> <!-- this closes the .wrap div -->
</body>
</html>
```

The CSS:

```css
.wrap {
  width: 700px;
  margin: 0 auto;
}
```

## In-class Activity

Over the next few classes, you will create a small website that showcases a band’s album releases.

### Steps

Choose a music artist of band that has at least 4 releases and at least two band members.

Find the band members names' and a little background information about them. You can use information found on the Web or other sources. **Just make sure to cite and link to your source.**

For each of 4 of their albums, find the title, track listing, and cover art.

Gather, edit, and organize copy. Make sure that you keep a record of your sources. Add the appropriate content to your HTML documents. Keep reading to know what copy you need to gather, edit, and organize.

In your DMD1070 folder, create a new folder named **discography**.

Create 2 html files:

- index.html
- discography.html

index.html should have:

- Band/artist name
- Image of the band/artist
- Background information
- Unordered list of band members
- Table with 2-columns
  - Year album was released
  - title of the album

**discography.html should have, for *each* album:**

- A div with a unique id
- Inside the div have:
  - Title of album
  - The album cover art
  - Ordered list of track listing
  - Link (Back) to about page

This activity is originally from [Teach the Web](http://teachtheweb.com/course_materials/discography_1.php)