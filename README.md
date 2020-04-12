# htmlcheatsheet
## Overview
Hands-on coding exercises to learn HTML(Hyper Text Markup Language) by following [HTML Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=UB1O30fR-EE)

The video is about 1 hour long, which covers all of the common HTML5 tags, attributes, semantic markup, etc.

## What is HTML
HTML is a defined standard markup language for creating webpages / documents NOT a programming language.


## HTML Page Structure (index.html)
`index.html` is the root / home page of a website

    <!DOCTYPE html>
    <html>
        <head>
            <title>Page title</title>
        </head>

        <body>
            <h1>This is a heading</h1>
            <p>This is a paragraph</p>
            <p>This is another paragraph</p>
        </body>
    </html>


## Inline .vs Block Level Elements
Block Level: `<div>`, `<h1>`-`<h6>`, `<p>`, `<form>`

* Start on a new line
* Take full width available

Inline Level: `<span>`, `<img>`, `<a>`

* Do not start on a new line
* Take only the necessary width


## Tag Syntax
`<tagname>content</tagname>`


## Tag Attributes
All tags can have attributes which provide information about an element.
`<tagname> attributename="attributename">content</tagname>`


## HTML5 Semantic Tags (blog.html)
A semantic element clearly describes its meaning to both the browser and the developer

    <header></header>
    <footer></footer>
    <aside></aside>
    <main></main>
    <article></article>
    <nav></nav>
    <section></section>
    <details></details>

Layout:

    +---------------------------+
    |         <header>          |
    +---------------------------+
    |         <nav>             |
    +---------------------------+
    |  <section>    |           |
    +---------------|  <aside>  |
    |  <article>    |           |
    +---------------------------+
    |         <footer>          |
    +---------------------------+



