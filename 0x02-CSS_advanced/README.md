# 0x02. Advanced CSS

In this project we will be styling [index.html](/0x00-html_advanced/index.html) from [0x00. Advanced HTML](/0x00-html_advanced/README.md) with advanced CSS concepts.
Concepts covered in this project:

-   [CSS fundamentals](https://intranet.hbtn.io/concepts/140)
-   [CSS advanced](https://intranet.hbtn.io/concepts/205)

## Resources

- [CSS Reference - A free visual guide to CSS](https://cssreference.io/)
- [Can I use,,, Support tables for HTML5, CSS3, etc](https://caniuse.com/)
- [CSS Reference](http://ref.openweb.io/CSS/)
- [CSS Properties | HTML Dog](https://htmldog.com/references/css/properties/)
- [Box Sizing](https://css-tricks.com/box-sizing/)
- [CSS Selectors weight](https://www.w3schools.com/css/css_specificity.asp)
- [CSS specificity calculator](https://specificity.keegan.st/)
- [Play with CSS selector](https://frontend30.com/css-selectors-cheatsheet/)

## Learning Objectives

- Selectors, properties, and values
- The difference between block and inline styling
- How to ensure consistency across all browers (CSS reset)
- How to setup CSS variables
- The differences between inline, embeded and external CSS
- How grid systems work (with floats)
- The difference between icons webfonts and SVG icons
- The difference between pseudo-classes and pseudo-elements
- How to make background gradients
- How to animate elements in CSS
- How to transform (2d, 3d) elements
- What vendor prefixes are

## Quiz questions

- **Question #0**: What’s the font-size in pixel of an element p.my_class?
```css
p {
    font-size: 12px;
}
p.my_class {
    font-size: 1em;
}
```
Answer: `12px` (12 * 1 = 12)
- **Question #1**: What’s the impact of position: fixed on an element? `the element position will be relative to the viewport`
- **Question #2**: What’s the font-size in pixel of an element p.my_class if the default p font-size is 16px?
```css
p {
    font-size: 75%;
}
p.my_class {
    font-size: 2.25em;
}
```
Answer: `27px` (16 * 0.75 * 2.25 = 27)
- **Question #3**: What’s the font-size in pixel of an element p.my_class if the default p font-size is 16px?
```css
p {
    font-size: 12px;
}
p.my_class {
    font-size: 2.25rem;
}
```
Answer: `36px` (16 * 2.25 = 36)
- **Question #4**: What’s the `font-size` in pixel of an element `p.my_class` if the default `p`  `font-size` is 16px?
```html
<html>
    <head>
        <style>
            body {
                color: #00FF00;
            }
            h1 {
                color: #FF0000;
            }
        </style>
    </head>
    <body>
            <h1>Hello</h1>
    </body>
</html>
```
Answer: `#FF0000` (h1 is more specific than body)
- **Question #5**: What’s z-index? `z-index is defining the stack position of an element (from front to background)`
- **Question #6**: What’s the final color text of `<h1>` in this code?
```html
<html>
    <head>
        <style>
            body > h1.title {
                color: #FF0000;
            }
            h1.title {
                color: #00FF00;
            }
            body h1 {
                color: #0000FF;
            }
        </style>
    </head>
    <body>
            <h1 class="title">Hello</h1>
    </body>
</html>
```
Answer: `#FF0000` (body > h1.title is more specific than h1.title)
- **Question #7**: padding is adding space between? `Between the inside content and the border of the element`
- **Question #8**: What’s the font-size in pixel of an element p.my_class?
```css
p {
    font-size: 12px;
}
p.my_class {
    font-size: 1.5em;
}
```
Answer: `18px` (12 * 1.5 = 18)
- **Question #9**: What’s the final color text of `<h1>` in this code?
```html
<html>
    <head>
        <style>
            h1, h2 {
                color: #FF0000;
            }
        </style>
    </head>
    <body>
            <h1>Hello</h1>
    </body>
</html>
```
Answer: `#FF0000`
- **Question #10**: What’s the final color text of `<h1>` in this code?
```html
<html>
    <head>
        <style>
            h1 {
                color: #FF0000;
            }
            body h1 {
                color: #00FF00;
            }
        </style>
    </head>
    <body>
            <h1>Hello</h1>
    </body>
</html>
```
Answer: `#00FF00`
- **Question #11**: What’s the font-size in pixel of an element p.my_class?
```css
p {
    font-size: 12px;
}
p.my_class {
    color: #FF0000;
}
```
Answer: `12px`
- **Question #12**: What’s the font-size in pixel of an element p.my_class if the default p font-size is 16px?
```css
p {
    font-size: 12px;
}
p.my_class {
    font-size: 0.25rem;
}
```
Answer: `4px` (16 * 0.25 = 4)
- **Question #13**: What’s the final color text of `<h1>` in this code?
```html
<html>
    <head>
        <style>
            h1 {
                color: #FF0000;
            }
        </style>
    </head>
    <body>
            <h1>Hello</h1>
    </body>
</html>
```
Answer: `#FF0000` (h1 is more specific than body)
- **Question #14**: What’s the final color text of `<h1>` in this code?
```html
<html>
    <head>
        <style>
            h1 {
                color: #FF0000;
            }
            h1.title {
                color: #00FF00;
            }
            body h1 {
                color: #0000FF;
            }
        </style>
    </head>
    <body>
            <h1 class="title">Hello</h1>
    </body>
</html>
```
Answer: `#00FF00` (h1.title is more specific than h1)
- **Question #15**: What’s the final color text of `<h1>` in this code?
```html
<html>
    <head>
        <style>
            h1.title {
                color: #FF0000;
            }
        </style>
    </head>
    <body>
            <h1>Hello</h1>
    </body>
</html>
```
Answer: `Black (default value)`
- **Question #16**: margin is adding space between? `Between the border of the element and external elements (parent and siblings elements)`
- **Question #17**: What’s the impact of overflow-y: auto on an element?`the element allows vertical scrolling if the content is too long`
- **Question #18**: What’s the impact of position: absolute on an element? `the element position will be relative to the nearest positioned ancestor element`
- **Question #19**: What’s the final color text of `<h1>` in this code?
```html
<html>
    <head>
        <style>
            body {
                color: #00FF00;
            }
        </style>
    </head>
    <body>
            <h1>Hello</h1>
    </body>
</html>
```
Answer: `#00FF00` (body is more specific than h1)
- **Question #20**: What’s the font-size in pixel of an element p.my_class?
```css
p {
    font-size: 12px;
}
p.my_class {
    font-size: 0.25em;
}
```
Answer: `3px` (12 * 0.25 = 3)