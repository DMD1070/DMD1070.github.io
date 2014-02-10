---
layout: post
title: Web Typography
lesson_num: 07
---

<p class="lead">Some would argue that [Web Design is 95% Typography](http://ia.net/blog/the-web-is-all-about-typography-period/_). Carefully considering the type of our website will greatly improve the design of our site as well as making it easier for our users to read and scan for information.</p>

## Typography Overview

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

```
h2 {
  font-size 1.5em;
}

If math isn't your thing, the [pxtoem.com](http://pxtoem.com/) takes a lot of the guess work our of conversions.

## Hierarchy

## Line Length

## Finding Typefaces

## In Class Activity 1

## In Class Activity 2
