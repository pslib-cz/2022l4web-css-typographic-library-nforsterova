# Typography CSS library
**Author:** *Nikol Forsterová*
## Description
This typhography CSS library was created for a school project. It simplifies the beginnings of other projects. You don't need to create new css for essential things like haedings or lists every time you start some project. You can style your headings, lists, pictures and more with help of this library.
## Demo site
Link to **[demo](./index.html)** site for preview.
## Content of the documentation
1. [Implementation](#Implementation)
2. [Headings](#Headings)
3. [Types of text](#Types-of-text)
4. [Lists](#Lists)
    1. [Ordered list](#Ordered-list)
    2. [Unordered list](#Unordered-list)
5. [Buttons](#Buttons)
6. [Pictures](#Pictures)
7. [End](#the-end)
## Implementation
1. Download Typhography library in  **[documents/download](./)** folder
2. Add this file to your project 
3. Link style.css to `<head>` in every HTML page by using:
    ```html
    <link href="maestro.css" rel="stylesheet">
    ```
## Headings 
This CSS library includes styled headings from `<h1>` to `<h2>`. They have two colors and different sizes: 
* 30px for `<h1>`
* 24px for `<h2>`
* 19px for `<h3>`
* 16px for `<h4>`
* 13px for `<h5>`
* 10px for `<h5>`
## Types of text
Other types of text you can use are:
- `<u>` for __underlined__ text
- `<b>` for **bold** text
- `<s>` for ~~striked~~ text
- `<mark>` for marked text with color
- `<i>` for *italic* text
- `class="small"` for small text
- `class="all-caps"` for CAPS text
## Lists
### Ordered list
For ordered lists we use `<ol>` tag. For his items we use `<li>` tags. Syntax:
```html
<ol>
    <li>First item that have more items
        <ol>
            <li>First item detail</li>
            <li>Second item detail</li>
        </ol>
    </li>
    <li>Second item</li>
</ol>
```
### Unordered list
For ordered lists we use `<ul>` tag. For his items we use `<li>` tags. Syntax:
```html
<ul>
    <li>Item
        <ul>
            <li>More of item</li>
            <li>More of item</li>
        </ul>
    </li>
    <li> Another item</li>
</ul>
```
## Buttons
If you want to use some clikable buttons in your project, you can use `<button>` tag. In this library, there are three types of buttons. You use them by adding class:
- Use class `class="btn-buy"` for purple button.
- Use class `class="btn-save"` for button that changes colors.
- Use class `class="btn-warning"` for warning button.
## Pictures
With help of element `<img>` we add an image into our document. There is an example of how to do that:
```html
<figure class="img__box">
    <a href="./img/picture.jpg">
        <img src="./img/picture.jpg" alt="some alternative text">
        <figcaption class="img__caption">Any caption you write</figcaption>
    </a>
</figure>
```
## The end
I hope you find this CSS typhography gallery helpful in your projects:)
