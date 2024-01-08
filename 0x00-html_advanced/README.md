# 0x00. Advanced HTML

In this project, we will learn how to use HTML tags to structure a web page. No CSS, no styling - don’t worry, the final page will be “ugly” it’s normal, it’s not the purpose of this project.

## Resources

- [HTML 5.2](https://html.spec.whatwg.org/multipage/)
- [HTML: HyperText Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML Reference - A free guide to all HTML elements and attributes](https://htmlreference.io/)
- [Can I use… Support tables for HTML5, CSS3, etc](https://caniuse.com/)
- [HTML Cheat Sheet - WebsiteSetup](https://websitesetup.org/html5-cheat-sheet/)

## Learning Objectives

- Which guidelines to follow for HTML
- How to create the skeleton of an HTML5 page
- How to use semantic HTML tags to structure a web page
- Which use cases to use `div` vs `span`
- The semantic value’s of `header`, `main`, `footer`, `article`, `nav`, `section`, `aside`
- How to use headings (and why it’s important to follow the hierarchical order)
- How to make lists in HTML
- The differences between medias (SVG, GIF, PNG, JPG)
- How to structure data in a table
- How to integrate a video in a webpage
- How to integrate an audio file in a webpage
- How to embed external content
- How to correctly structure an HTML page

## Quiz questions

- **Question #0**: Which tag should we use to group elements in an unordered list? `<ul>`
- **Question #1**: Which tag should we use to embed an image? `<img>`
- **Question #2**: Which tag should we use to embed another website? `<iframe>`
- **Question #3**: Which tag should we use to change the browser tab text? `<title>`
- **Question #4**: Which tag should we use to create an hyperlink? `<a>`
- **Question #5**: Which information can we find in the tag head? Please select all correct answers
    - [x] metadata
    - [ ] navigation
    - [ ] link to Twitter
    - [x] link to stylesheets
- **Question #6**: Which tag should we use to change the font weight of a text? <br> Please select all correct answers
    - [ ] `<h1>`
    - [ ] `<em>`
    - [ ] `<i>`
    - [x] `<b>`
    - [x] `<strong>`
    - [ ] `<bold>`
- **Question #7**: How many levels are available in HTML5 for section headings? 6
- **Question #8**: Which tag should we use to draw an horizontal line? (usually used to separate topics in a paragraph) `<hr>`

## Tasks (3 out of 40...)

<details>
<summary>0. Create your first webpage</summary>

Create your first HTML file [`0-index.html`](./0-index.html) with:

- Add the doctype on the first line (without any comment)
- After the doctype, open and close a `html` tag
- Add the language tag, specify English for [ISO language code](https://www.sitepoint.com/iso-2-letter-language-codes/) and add the direction tag (ltr or rtl) on the `html` tag
- Open your file in your browser (the page should be blank)
</details>

<details>
<summary>1. Structure your webpage</summary>

Copy the content of [`0-index.html`](./0-index.html) into [`1-index.html`](./1-index.html)

**Create the head and body sections**
- inside the `html` tag, create the `head` and `body` tags (empty) in this order
</details>

<details>
<summary>2. The head - meta charset, viewport, title, description, favicons</summary>

Copy the content of [`1-index.html`](./1-index.html) into [`2-index.html`](./2-index.html)

**Meta charset:**
- add a `meta` tag inside the `head`:
    - add the `charset` attribute with the value `utf-8`

**Viewport:**
- add a `meta` tag inside the `head`:
    - add an attribute `name` on the tag and specify that it is the meta `viewport`
    - add the key `width` with the value `device-width`
    - add the key `initial-scale` with the value `1.0`
    - add the key `viewport-fit` with the value `cover`

**Title:**
- add a `title` tag just after the meta viewport with value: `Homepage - Techium`

**Description:**
- add a `meta` tag inside the `head` section:
    - add an attribute `name` on the tag and specify that it is the meta `description`
    - add another attribute called `content`
    - add the following description: `Techium is a digital agency`

**Favicons:**
- dowload [this image](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/11/2ba3a0d7878316de5aaa.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240108%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240108T070652Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=c3d11c7c8889f9f76a691a54e48a499b7bd4b840fc205dbc01259862c4782b18) to use as a favicon
- use the tool at <https://realfavicongenerator.net/> to generate all the favicon formats
- take the `favicon.ico` and `favicon.png` and place these at the root of your project directory, so that it is siblings with your `[0-9]+-index.html` files.
- inside the `head`, create 2 `link` tags with these 3 attributes: `rel`, `type`, and `href`.
    - the first `link` tag:
        - rel: `icon`
        - type: `image/x-icon`
        - href: `./favicon.ico`
    - the second `link` tag:
        - rel: `icon`
        - type: `image/png`
        - href: `./favicon.png`
</details>

<details>
<summary>3 to 40</summary>

### I got tired guys, I'm sorry. I'll finish this later.
</details>