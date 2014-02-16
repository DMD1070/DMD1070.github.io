---
layout: post
title: Web Typography
lesson_num: 07
---

<p class="lead">Some would argue that [Web Design is 95% Typography](http://ia.net/blog/the-web-is-all-about-typography-period/_). Carefully considering the type of our website will greatly improve the design of our site as well as making it easier for our users to read and scan for information.</p>

## Typography Overview

### The History of Typography – Animated Short

<iframe width="560" height="315" src="//www.youtube.com/embed/wOgIkxAfJsk" frameborder="0" allowfullscreen></iframe>

### Typography | Off Book

<iframe width="560" height="315" src="//www.youtube.com/embed/eKKDL6lekmA" frameborder="0" allowfullscreen></iframe>

## Exploring Typography Activity

### Part 1

Type is [all around us](http://www.flickr.com/groups/found-typography/). Take the next hour to explore te typography of the campus/surrounding area. Take photos of type that you find interesting and be sure to photograph **all 26 letters of the alphabet.**

### Part 2

Create a 900 x 750 Photoshop document with a white background. Click *View > Show Grid*.

Open each letter photo in Photoshop. Set your crop to 100 x 100 and crop the letters. Once cropped bring the letter into the large Photoshop document.

Use the white space in the bottom right corner to type set your name. When you are finished. Save the image for the web as a jpg file: *File > Save for Web and Devices > Preset: JPEG, Quality: High* and post the image to your class blog.

## Sizing Type

Up until now we've been sizing our type with with the px unit of measure, but from here on out we'll be using `ems`. There's a [number of reasons](http://css-tricks.com/why-ems/) to use ems over px, but most importantly is te flexibility it gives us as designers.

Our body font size is set to 100%, which is equivalent to 16px. Ems are a *relative* unit of measure, so we will use our base size of 16px to calculate our other type sizes.

The basic formula is as follows:

```
Desired font size / 16 = em measurement
```

For example, if we'd like a type size of 24 for an h2, we'd calculate it as such:

```
24 / 16 = 1.5
```

And our CSS would be:

```css
h2 {
  font-size 1.5em;
}

If math isn't your thing, the [pxtoem.com](http://pxtoem.com/) takes a lot of the guess work our of conversions.

## Hierarchy

Having a clear hierarchy will improve the legibility and scanability of your page. Here's a solid baseline for projects:

```css
h1 {
  font-size: 3em; /* 48px */
}

h2 {
  font-size: 2.25em /* 36px */
}

h3 {
  font-size: 1.75em /* 28px */
}

h4 {
  font-size: 1.125em /*18px */
}

p {
  font-size: 1em /* 16px */
}
```

## Line Length

## HTML Entities

## Finding Typefaces

### Font Stacks

### @font-face

### Web Font Services

Be sure to take a look at [The Best Google Web Fonts](http://hellohappy.org/beautiful-web-type) demo

## Web Type Activity 1

## Web Type Activity 2

## This Week's Assignments

### CodeAcademy

Complete lessons 7, 8, 9, and 10 of the [HTML & CSS track](http://www.codecademy.com/tracks/web). Send me a screenshot showing completion prior to next week's class.

### Blog Post
Complete the found alphabet activity and post it to your blog.

### Reading

