---
layout: post
title: Intermediate HTML & CSS
lesson_num: 05
---

<p class="lead">Now that we know the basics of HTML and CSS, let's level up by introducing new tags and ways to style things.</p>

## Intermediate HTML

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

## Activity