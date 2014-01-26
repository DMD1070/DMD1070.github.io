---
layout: post
title: Hello World
lesson_num: 01.
class_date: January 21, 2014
categories:
- lesson
---

Welcome to DMD1070, Foundations of Web Design. This course is designed to guide you through the process of planning, designing, and implementing your first website. In this lesson we'll gain our bearings by understanding a bit about the history of the web and how the web works.

<!--more-->

[Jump to the assignments](#assignments)

<iframe src="//slid.es/ascott1/dmd1070-1/embed" width="576" height="420" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

## How Does the Web Work?

The Web is built on a series of technologies for information transfer, plus some programming languages that you use to specify how you want that information to look. A simplified view follows:

- **The client:** This is your computer, which you use to access the Web
- **The server:** This is a computer in a room somewhere, which stores websites. When you access a website on your computer, a copy of the website data is sent from the server to your client machine for you to look at.
- **Your Internet connection:** Allows you to send and receive data on the Web. It's basically like a giant street that cars and people can travel down.
- **TCP/IP:** Defines how your data should travel down that road. This is like the cars and buses people use to get places.
- **HTTP:** Defines how and when data should be sent between the client and the server. This is like some people deciding what journeys they need to go on down the road, how far they need to travel, what mode of transport they need to use, etc.
- **DNS:** Domain Name Servers are like an address book for Websites. When you type in a web address in your browser, before the website is retrieved the browser goes to the DNS to find out where it lives, like when you look up someone's address so you can go and visit them. Try typing http://212.58.251.195 into your web browser.
- **HTML, CSS and JavaScript:** The main three programming languages that websites are built from.
- **Assets:** This is a collective noun for all the other stuff that makes up a website, such as image files, MP3s and videos, Word documents, PDFs, etc.

## Activity 1: The Wayback Machine

Choose a popular website and enter its URL into the [Wayback Machine](https://archive.org/web/). Browse through at least 5 dates of the site's history and note the following:

- How has the design of the site changed?
- How has the content of the site changed?
- What are some similarities between past and current versions of the site?

## Activity 2: Life Without the Web

What was life like before the web? Try to imagine (or recall) how you would accomplish these tasks without the web:

- Read the menu of a local restaraunt
- Buy concert tickets
- Find the best driving route to Portland, Maine
- Book a trip to San Francisco
- Find out the score of a football game
- Check the balane of your bank account
- Find out if the dry cleaner is open
- Find the best price for a new pair of shoes

## Activity 3: A game of client/server

A game of client/server

Let's play a game! To play this we need:

- Some lego bricks (or some coloured cards of some kind)
- One person to play a web server
- One person to play HTTP
- 2-3 people to play clients
- One person to play DNS
- and a decent number of people to play our website data.

First, a typical successful web request:

1. First the clients request a web page
2. The client web browsers look up the IP address of the website using the DNS
3. HTTP informs the server that the clients are requesting a website, with a message sent to the server. This is called an HTTP request.
4. There is no reason why the clients can't have this website, so the server responds with "200, OK". HTTP gives this response back to the client.
5. The website data is sent down the pipe to the clients. A copy is sent to each.
6. The clients assemble the data into a working website that it's users can interact with.

Now, an unsuccessful web request:

1. First the clients request a web page, but they've got the address slightly wrong.
2. The client web browsers look up the IP address they've been given using the DNS
3. The website cannot be found, so the HTTP response "404, NOT FOUND" is given back to the client.

When data is sent down the pipe, it is broken up into little tiny bits called packets. Each one of our data people really represents a single packet! If the data were not broken into packets before being sent to the client computers, it would be much harder to send around. It's the same principle as getting a wardrobe in through your front door, up your stairs and into your bedroom. This is a lot easier to do if you carry the wardrobe upstairs in pieces and then assemble it in the bedroom, rather than carrying it upstairs already assembled!

## Activity 4: View the Web Through X-Ray Goggles

Using Mozilla's [X-Ray Goggles](https://goggles.webmaker.org/) let's remix a web page.

1. [Together] Click the link above and follow the "See how Goggles work by swapping an image" instructions.
2. Install the X-Ray Goggles bookmarklet by dragging the "Activate X-Ray Goggles" link to your bookmarks bar.
3. Now let's remix the web! Choose a popular website and tweak it to achieve interesting, outlandish, or provoking results.

<a id="assignments"></a>

## Readings & Assignments

### 1. Read Tim Berners-Lee's ["The World Wide Web: A very short personal history"](http://www.w3.org/People/Berners-Lee/ShortHistory.html)

Read the Web inventor's brief personal history. Do you think his vision of the web has held true? Come to class on Thursday prepared to discuss this.

### 2. Set Up Your Blog 

Throughout the semester we will be utilizing a WordPress blog. 


Go to [Wordpress.com](http://www.wordpress.com) to create and maintain your blog. Wordpress is a free content management tool.

Your blog’s URL should be your first and last names (with a number if needed). For example mine might be: http://adamscott.wordpress.com or http://adamscott2014.wordpress.com

Follow the instructions on wordpress.com in order to create your blog. After you set up your blog, familiarize yourself with the “dashboard.” This is where you manage your blog. Choose from the themes that are provided and follow the instructions to add your own images to the theme. Customize the theme to make it feel more like your own design style (you do this within the dashboard).

Create a category titled “DMD1070.” Throughout the semester you will be required to post entries to your blog. The entries for this class are to be put in the “DMD1070” category.

Inappropriate materials posted to your blog or comments on classmates' blogs will not be tolerated.

## Lesson Credits

Some of the content and activities of this lesson were adapted from [Teach the Web](http://teachtheweb.com/course_materials/wordpress.php) and [It's My Web](http://people.mozilla.org/~cmills/st-chads/)