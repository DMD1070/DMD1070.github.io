---
layout: post
title: Web Typography
lesson_num: 07
---

<p class="lead">Some would argue that <a href="http://ia.net/blog/the-web-is-all-about-typography-period/">Web Design is 95% Typography</a>. Carefully considering the type of our website will greatly improve the design of our site as well as making it easier for our users to read and scan for information.</p>

## Typography Overview

### The History of Typography – Animated Short

<iframe width="560" height="315" src="//www.youtube.com/embed/wOgIkxAfJsk" frameborder="0" allowfullscreen></iframe>

### Typography | Off Book

<iframe width="560" height="315" src="//www.youtube.com/embed/eKKDL6lekmA" frameborder="0" allowfullscreen></iframe>

## Exploring Typography Activity

### Part 1

Type is [all around us](http://www.flickr.com/groups/found-typography/). Take the next hour to explore the typography of the campus/surrounding area. Take photos of type that you find interesting and be sure to photograph **all 26 letters of the alphabet.**

### Part 2

Create a 900 x 750 Photoshop document with a white background. Click *View > Show Grid*.

Open each letter photo in Photoshop. Set your crop to 100 x 100 and crop the letters. Once cropped bring the letter into the large Photoshop document.

Use the white space in the bottom right corner to type set your name. When you are finished. Save the image for the web as a jpg file: *File > Save for Web and Devices > Preset: JPEG, Quality: High* and post the image to your class blog.

## Activity Type Setting an Article

Together let's type set Tim Berners-Lee's [The World Wide Web: A very short personal history](http://www.w3.org/People/Berners-Lee/ShortHistory.html)

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
```

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

Although they can easily be found [all](http://amazon.com) [over](http://wikipedia.org) the web, long line lengths are difficult to read.


## HTML Character Entities

Character entities are used to print special characters in HTML. Some are essential such as the less-than and greater-than symbols which are used in HTML tags. To display a greater-than symbol on a web page, you must use a character entitites. Character entities also give us greater control over our typography.

[Here is a full list of HTML character entities](http://www.dionysia.org/html/entities/symbols.html)

## Finding Typefaces

### Font Stacks

We've already discussed font stacks briefly while learning the basics of CSS. While we don't have the control or amount of choice in type that the following methods will discuss, there are still several benefits to using native typefaces with font stacks. Mainly:

- They are quick to load (the user doesn't need to download them)
- They render nicely (web fonts can look less than great on certain operating systems)

### @font-face

@font-face is a way of using font-files so that all users are served the typeface you've chosen for your site design. [Font Squirrel](http://www.fontsquirrel.com/) has a great directory of free fonts and creates downloadable @font-face kits for you.

### Web Font Services

There are a handful of services that take the guess work out of using @font-face.

[Typekit](https://typekit.com/) uses professional typefaces, but the free plan can only be used on one site.

[Google Web Fonts](https://www.google.com/fonts) uses free and open source fonts (similar to Font Squirrel), but makes adding the the fonts to a page *really* easy. 

Be sure to take a look at [The Best Google Web Fonts](http://hellohappy.org/beautiful-web-type) demo

## Web Type Activity 1

Choose a quote or song lyric and try creating a typographic interpretation, similar to those found at [The Best Google Web Fonts](http://hellohappy.org/beautiful-web-type) demo. Try to be creative, but **do not use more than 2 fonts.**

## Web Type Activity 2

We can do a better job than the last style sheets used in our Discography projects by creating a *new* style sheet for this website. This style sheet will be used for both pages.

Create a new style sheet for your Discography website. Link the style sheet in both HTML documents.

Make appropriate typography decisions such as:

- font
- line length
- line height
- visual hierarchy
- Make everything legible and readable.

Your links need to have 4 states:

- link
- visited
- hover
- active

Use ems for your unit of measurement.

## This Week's Assignments

### CodeAcademy

Complete lessons 7, 8, 9, and 10 of the [HTML & CSS track](http://www.codecademy.com/tracks/web). Send me a screenshot showing completion prior to next week's class.

### Blog Post
Complete the found alphabet activity and post it to your blog.

### Reading

**Focus on the concept not the technical how-to for now**

- [Responsive Web Design](http://alistapart.com/article/responsive-web-design/)
- [Responsive Web Design: What It Is and How To Use It](http://coding.smashingmagazine.com/2011/01/12/guidelines-for-responsive-web-design/)

