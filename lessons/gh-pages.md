---
layout: post
title: Getting a site on the web with GitHub pages
lesson_num: 0
published: true
excerpt: "Now that you have some HTML and CSS, let's get it on the web with GitHub."
---

So you’ve made a website with HTML and CSS, that’s awesome! Well done! Right now that site only lives on your computer rather than being accessible to the world. Boo! Let’s fix that!

We’ll be using the site GitHub.com. GitHub is a collaborative code sharing site, used by many developers. One of the cool features it has is that we can use it to host HTML web sites “GitHub Pages.”

Let’s go!

### 1. Sign up for GitHub

If you don’t already have an account, create one at [github.com/join](https://github.com/join)

### 2. Create a new repository

From GitHub’s homepage click the “+ New Repository” button.

![](/lesson_files/gh-pages/02-button.png)

Give the repository a name.

**Important**: Check the box that says “Initialize this repository with a README.”

![](/lesson_files/gh-pages/02-readme.png)

### 3. Drag and drop your files

Select all of the files for your webpage on your computer and drag and drop them onto your repository page.

![](/lesson_files/gh-pages/03-drag.png)

Click the **Commit Changes** button.

![](/lesson_files/gh-pages/03-commit.png)

### 4. Create a gh-pages branch

For GitHub to serve a site live on the web, it must be on what it calls the `gh-pages` branch. Let’s create that branch:

Click the drop down menu that says **Branch: master**

![](/lesson_files/gh-pages/04-branch1.png)

Type `gh-pages` into the input and click enter.

![](/lesson_files/gh-pages/04-branch2.png)

### 5. Make gh-pages the default branch

From your repository page, click Settings

![](/lesson_files/gh-pages/05-menu.png)

From the settings screen, click branches (on the left)

Under “Default Branch” select `gh-pages` and click **Update**

![](/lesson_files/gh-pages/05-default.png)

### 6. View your site

Your site should now be live on the web!

The URL will be:

https://YOUR_USERNAME.github.io/THE_REPOSITORY_NAME

Give yourself a high five!

![](/lesson_files/gh-pages/five.gif)

### To update your site with changes

Just repeat step 3!
