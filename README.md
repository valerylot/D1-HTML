# HTML

- To get the template: `!` + `tab`.

## What is HTML?
- HTML stands for **HyperText Markup Language**.
- HyperText: text that can link to other text. That's what links are.
- Markup: labels around the content that tell the browser what each piece is.
- HTML is a markup language, not a programming language. It describes content. It doesn't make decisions or do math.


## Tags vs Elements
- Tag: `<h1>` opens, `</h1>` closes. The `/` makes it a closing tag.
- Element: the opening tag + the content + the closing tag together

## Headings
- `<h1>` to `<h6>`. `<h1>` is the most important, `<h6>` is the least.
- Headings are about ranking, not size.
- Don't use a heading just to make text big.


## Nesting
- Elements can go inside other elements. Outer = parent, inner = child.
- Close the inner one before the outer one. Elements never overlap.

## alt text
- `alt` describes the image. it shows if the image can't load, and screen readers read it out loud.

## Landmarks
- `<header>` , `<main>`, `<footer>` say what a section of the page is.
- They don't change how the page looks.

## Links and Paths
- `<a href="...">` makes a link. `href` is where it goes.
- Paths start from the file I'm in:
    - `contact.html` = a file right next to me.
    - `pages/contact.html` = go into the pages folder
    - `..index.html` = go up one folder (this gets you out of the folder)

## Forms
- `<label for="x">` connects to `<input id="x">`. You want to make sure the FOR matches the ID. Clicking the label jumps into the input.
- `type` changes what an input does: text, email, number, radio, and checkbox.
