# Section 1: Welcome and First Steps
## A High-Level Overview of Web Development
### Front-end vs. Back-end Development
Accessing a page from the browser:
- browser will send a request to the web server where the website is hosted
- each website is hosted on a server and is able to receive requests
- when the server recieve request, retrieve all files and send a response back to browser (files that the website is made of)
- filetypes include .html, .css, .js, and .jpg, etc. that browsers can understand
- all code that makes up websites needs to be written in the above.
- website takes code and renders website based on the code.
- Static websites: files sent to the website as they are

back-end development to take information from database and organises the information into content to return to the requesting website - Dynamic website dynamically-assembled from different pieces.

### The three languages of front-end
1. HTML
   - Responsible for content on the page
   - e.g. text, images, buttons, etc.
   - written inside html file
   - represents Nouns, e.g. `<p></p>`
2. CSS
   - responsible for the presentation of that content.
   - compiling and laying out elements on webpage
   - represents Adjectives, e.g. `p {color: red}`
3. Javascript
   - actual frontend programming language
   - allows us to add dynamic effects and web applications.
   - represents Verbs, e.g. `p.hide()`
## Your very first Webpage
1. Each website needs an `index.html` - a landing page.
2. "cheat" in VSCode - typing `!` then `tab` will have generate a simple and basic html structure.
3. General structure
   - `<body>` is what you will see in the webpage
   - `<title>` is displayed in the tab.
   - `<h1>` stand for "header 1"
   - `<p>` stands for "paragraph" 

# Section 2: HTML Fundamentals
## Introduction to HTML
- `H`yper`T`ext `M`arkup `L`anguage
- markup language (**not** a programming language)
- structure and describe the entire content of a webpage
- consist **elements** that describe different types of content
  - paragraphs `<p>`, links, headings, images, video, etc.
- Web browsers understand HTML and can render HTML code as websites.

### Anatomy of an HTML element
e.g. `<p>HTML is a markup language</p>` is an element. Made up of three parts:
1. Opening tag: name of element, wrapped in `<>`
2. Content: content of element. might be another element (child element), or no content, e.g. `<img>`
3. Closing tag: same as opening tag, but with `/`. When element has no content, it is omitted.

## HTML Document Structure
Structure that each and every HTML document needs to have.
1. Declare doctype. `<!DOCTYPE html>`
2. Create a HTML element. `<html></html>`
   - each HTML document needs to start with this, **including one head and body** element 
4. Put another element in content. `<head></head>`
  - things that are not visible in the browser window
  - title, some additional infomation
  - link to CSS files
  - for now, specify title `<title>The Basic Language of the web: HTML</title>`
6. Another element in content. `<body></body>`
  - All elements visible in the browser window.
  - what you want rendered on the page should go into the body.
  - add a header `<h1>The Basic Language of the Web: HTML</h1>`

Putting it together:
```html
<!doctype html>
<html lang="en">
  <head>
    <title>The Basic Language of the Web: HTML</title>
  </head>

  <body>
    <h1>The Basic Language of the Web: HTMLs</h1>
  </body>
</html>
```
## Text Elements
New elements for working with text.

### Headings
Goal is to break up big blocks of text into logical sections and add a title to each of the sections.

There are six different headings:
1. h1 to h6.
2. h1 - primary heading, h2 - secondary, etc.
3. Creates a visual hiearchy between the six headings, first one is biggest one, sixth is smallest.

### Paragraphs
The paragraph element, a generic element to markup bigger blocks of text.

To write a comment, `<!--any comment here-->`

# Section 3: CSS Fundamentals

# Section 4: Layouts: Floats, Flexbox, and CSS Grid Fundamentals

# Section 5: Web Design Rules and Framework

# Section 6: Components and Layout Patterns

# Section 7: Omnifood Project - Setup and Desktop Version

# Section 8: Omnifood Project - Responsive Web Design

# Section 9: Omnifood Project - Effects, Optimizations and Deployment
