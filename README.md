# Build a web page - HTML - Lesson 1

## Overview

Today we are going to use [HTML](http://en.wikipedia.org/wiki/HTML) to help us tell a story in the web browser that we can show our friends and family.

```html
<p>HTML is a markup language that we can use to add structure and formatting to our story in web browsers, like Safari or Chrome. When we use HTML to tell a story in the web browser, we are creating a web page.</p>
```

A web page is made up of many html elements, each a tag, or more commonly a set of tags, enclosed in angle brackets. The paragraph above is an example of how you mark a paragraph in html, by surrounding it in opening and closing `<p>` tags.

**Description**

To get started in web development we'll need to learn how to use html, so today we are going to:

* Start with a basic HTML template
* Tell our story and use HTML to add structure and formatting

**Demo**

This bit of code:

```
<!DOCTYPE html>
<html>
  <head>
    <title>My day at work</title>
  </head>
  <body>
    <h1>My day at work</h1>
    <p>I had a good day at work. I was able to accomplish my goals and mentor a colleague.</p>
    <p>My goals included:</p>
    <ul>
      <li>Implement <strong>like</strong> feature</li>
      <li>Test emplementation in staging</li>
      <li>Deploy feature to production</li>
      <li>Blog about building and shipping the <strong>like</strong> feature</li>
    </ul>
    <p>When I think about it, today was actually an excellent day!</p>
  </body>
</html>
```

Will produce a web page that looks like this:

![demo](http://cl.ly/image/0e1d3b2C3y2P/content#.png)

Check out the [live demo](http://codepen.io/anon/pen/vmibf) to experiment yourself.

## Prerequisites

**Tools**

* [CODEPEN](http://codepen.io/pen/)

## Getting Started

To get started you should open a blank project on CODEPEN: [http://codepen.io/pen/](http://codepen.io/pen/)

![CODEPEN empty project](http://cl.ly/image/35081n120I42/content#.png)

For now ignore the JS and CSS areas so uncheck the boxes next to them.

![Uncheck JS and CSS](http://cl.ly/image/1f3C0E1O1t2Q/content#.png)

Now add the minimal amount of HTML to make the page work. Start by clicking in the HTML area and adding opening and closing `<html>` tags.

```html
<html>
</html>
```

Your screen should look like this now:

![CODEPEN after adding html tags](http://cl.ly/image/1y1H1M1n2r1m/content#.png)

Next add the `<head>` and `<body>` tags. The `<body>` tags tell the web browser that this part of the page should be rendered (displayed). Now our HTML should look like this:

```html
<html>
  <head>
  </head>
  <body>
  </body>
</html>
```

Now you can start telling your story by writing it out inside of the `<body>` tags! Here is an example:

```html
<html>
  <head>
  </head>
  <body>
    Today I took the dogs to the park and we had a great time!
  </body>
</html>
```

![Basic demo of HTML in action](http://cl.ly/image/2P3l3V1A302i/content#.png)

Now tell more of your story, what else happened?

```html
<html>
  <head>
  </head>
  <body>
    Today I took the dogs to the park and we had a great time!

    After the dogs played with their friends we took a walk around the track together.
  </body>
</html>
```

![Telling more of the story](http://cl.ly/image/2w1Q090V1b2t/content#.png)

Here you can see that I separated my paragraphs using new lines (on the right) but the text in the browser (on the left) didn't get separated into paragraphs. This is because I did not use HTML to add  paragraph (`<p>` tags) to my story.

Add the `<p>` around the paragraphs:

```html
<html>
  <head>
  </head>
  <body>
    <p>Today I took the dogs to the park and we had a great time!</p>
    <p>After the dogs played with their friends we took a walk around the track together.</p>
  </body>
</html>
```

![Adding paragraph tags](http://cl.ly/image/1U053V060k0u/content#.png)

Now the paragraphs are displayed correctly!

Next add a title to your story. To do this add the `<title>` to the `<head>` and then add it to the `<body>` using `<h1>` tags.

```html
<html>
  <head>
    <title>A day at the dog park</title>
  </head>
  <body>
    <h1>A day at the dog park</h1>
    <p>Today I took the dogs to the park and we had a great time!</p>
    <p>After the dogs played with their friends we took a walk around the track together.</p>
  </body>
</html>
```

![Story with title](http://cl.ly/image/1e352r043A1x/content#.png)

## TODO

* other html elements, like `<ul>` and `<img>`
* `<!DOCTYPE html>`
* tease future lessons with basic stylesheet and javascript in the `<head>`

## Other Resources

* http://www.codecademy.com/glossary/html
