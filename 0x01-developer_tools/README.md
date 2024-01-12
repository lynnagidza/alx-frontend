# 0x01. Developer tools

In this project, we will analyze this website https://dev-tools.alx-tools.com/.

## Resources

- [Chrome DevTools | Tools for Web Developers | Google Developers](https://developer.chrome.com/docs/devtools/)
- [Introduction | Down and Dirty with Chrome Developer Tools](https://blittle.github.io/chrome-dev-tools/)
- [Firefox Developer Tools | MDN](https://firefox-source-docs.mozilla.org/devtools-user/index.html)
- [Dev Tips - Developer Tips by Umar Hansa](https://umaar.com/dev-tips/)
- [Get Started With Viewing And Changing CSS | Tools for Web Developers](https://developer.chrome.com/docs/devtools/)
- [Keeping it simple with the JavaScript console - LogRocket Blog](https://blog.logrocket.com/keeping-it-simple-with-the-javascript-console/)
- [Inspect Network Activity - Chrome DevTools 101](https://www.youtube.com/watch?v=e1gAyQuIFQo)

## Learning Objectives

- What Developer Tools in your browser are
- How to open the Developer Tools on Chrome, Firefox, Safari, and Edge.
- How to use the elements tab to edit HTML and CSS
- How to audit a page according to the tips suggested by Lighthouse
- How to create and run snippets on a page
- How to get information about files and server configurations
- How to block requests
- How to know how much JavaScript or CSS is used on a page
- How to detect 404 issues
- How to move elements on a webpage

## Tasks

<details>
<summary>0. Responsive device</summary>

Go to `https://dev-tools.alx-tools.com/`

Take a screenshot of the website using the device toolbar Choose iPhone X and show the size in your screenshot (selected device or size in pixel of the rendering)
</details>

<details>
<summary>1. Change the background color</summary>

Go to `https://dev-tools.alx-tools.com/`

Change the background-color of the body to use `#4233bd` Take a screenshot of the `PORTFOLIO` section
</details>

<details>
<summary>2. Force element state</summary>

Go to `https://dev-tools.alx-tools.com/`

Force the hover state of the “cake” block in the section Portfolio Take a screenshot of it
</details>

<details>
<summary>3. Copy all the styles of the button</summary>

Go to `https://dev-tools.alx-tools.com/`

Select the `Download me!` and copy all the CSS styling that is applied on this button.

Your answer file must contain all CSS styling one per line like this example:
    
```
$ head -2 3-button_styles
border-radius: 1px;
color: #FF00FF;
$
```
</details>

<details>
<summary>4. Change button styles</summary>

Go to `https://dev-tools.alx-tools.com/`

All primary buttons (`btn-primary`) should have the `#0080ee` color as a background color
All outlined buttons light (`btn-outline-light`) should have `#0020aa` for the text color
Screenshot all buttons that changed and merge it to one image
</details>

<details>
<summary>5. Remove part of the website</summary>

Go to `https://dev-tools.alx-tools.com/`

Remove the `div` of the “cake” box in the section Portfolio

Take a screenshot of it
</details>

<details>
<summary>6. Where is it coming from?</summary>

Go to `https://dev-tools.alx-tools.com/`

- On the right panel, click on the `Computed tab`
- Then, select the `h2` with the text `ABOUT`
- Search for `margin-bottom`

Which file is coming from that declaration?
</details>

<details>
<summary>7. How many listeners</summary>

Go to `https://dev-tools.alx-tools.com/`

How many times click events are referenced in JavaScript files?
</details>

<details>
<summary>8. What is the HSL code</summary>

Go to `https://dev-tools.alx-tools.com/`

Select the primary button “Send”

What is the equivalent value of the hexadecimal background-color, in HSL?

(format of your answer should be: `hsl(<VALUES>);`, example: `hsl(241, 23%, 24%);` following by a new line)
</details>

<details>
<summary>9. The max-width of the container</summary>

Go to `https://dev-tools.alx-tools.com/`

What is the `max-width` for the first `.container` in the section “About”? (your browser width must be between 1250px and 1440px and with a zoom at 100%)

(format of your answer should be `max-width: <VALUE>;`, example: `max-width: 670px`)
</details>

<details>
<summary>10. Moving around</summary>

Go to `https://dev-tools.alx-tools.com/`

Switch the section “About” and “Portfolio”

Take a screenshot of it
</details>

<details>
<summary>11. Coverage</summary>

Go to `https://dev-tools.alx-tools.com/`

How many bytes that `freelancer.css` covers?

Answer file must contain the value in Byte (example: `6144` for 6KB)
</details>

<details>
<summary>12. Emulate the print version of the webpage</summary>

Go to `https://dev-tools.alx-tools.com/`

Take a screenshot of the homepage, only emulation the CSS print version of the website.
</details>

<details>
<summary>13. Using the console</summary>

Go to `https://dev-tools.alx-tools.com/`

Select the Avatar image in the header and type `$0` in the console. Enter.

What does it return?
</details>

<details>
<summary>14. Write code in the console</summary>

Go to `https://dev-tools.alx-tools.com/`

Write in the console `console.log(document.title)`, what is returned?
</details>

<details>
<summary>15. Web framework</summary>

Go to `https://dev-tools.alx-tools.com/`

Which front-end framework could we guess this page is using?

In your answer file only put the letter of the multiple choice answer from below:

- A. React JS
- B. Material Design
- C. Bootstrap
- D. Angular JS
</details>

<details>
<summary>16. Homepage weight</summary>

Go to `https://dev-tools.alx-tools.com/`

What is the total weight of the page (with all the elements)?

Take a screenshot of it
</details>

<details>
<summary>17. Number of requests</summary>

Go to `https://dev-tools.alx-tools.com/`

What is the number of requests done when accessing this page?

Take a screenshot of it
</details>

<details>
<summary>18. Number of CSS files</summary>

Go to `https://dev-tools.alx-tools.com/`

How many CSS resources are loaded on this page?
</details>

<details>
<summary>19. Number of images</summary>

Go to `https://dev-tools.alx-tools.com/`

How many image resources are loaded on this page?
</details>

<details>
<summary>20. Favicon image type </summary>

Go to `https://dev-tools.alx-tools.com/`

What is the `type` value of the favicon image?
</details>

<details>
<summary>21. Font library</summary>

Go to `https://dev-tools.alx-tools.com/`

The website uses a font library for their icons, which one is it?
</details>

<details>
<summary>22. XHR calls</summary>

Go to `https://dev-tools.alx-tools.com/`

What is the name of the resource that generates 1 XHR calls? 
</details>

<details>
<summary>23. Audits panel</summary>

Go to `https://dev-tools.alx-tools.com/`

What is the notation for `Performance` (for desktop mode and no throttling - also called Lighthouse)?

Take a screenshot of it
</details>

<details>
<summary>24. Static assets</summary>

Go to `https://dev-tools.alx-tools.com/`

How many static assets need a better cache policy?

Take a screenshot of it
</details>

<details>
<summary>25. Accessibility</summary>

Go to `https://dev-tools.alx-tools.com/`

When you run an accessibility audit, what is the contrast issue?

In your answer file only put the letter of the multiple choice answer from below:

- A. Image elements do not have [alt] attributes
- B. Links do not have a discernible name
- C. Background and foreground colors do not have a sufficient contrast ratio.
</details>

<details>
<summary>26. No alt</summary>

Go to `https://dev-tools.alx-tools.com/`

Which classes are on the images that have no `alt` attribute?

Your answer file must contains all classes, example: `.my_class.my_second` if 2 classes
</details>

<details>
<summary>27. Best practices</summary>

Go to `https://dev-tools.alx-tools.com/`

Which attribute is missing on all the links with the target `_blank`?

In your answer file only put the letter of the multiple choice answer from below:

- A. `rel="noopener"`
- B. `rel="noreferrer"`
- C. A and B
- D. `rel = "nofollow"`
</details>

<details>
<summary>28. SEO</summary>

Go to `https://dev-tools.alx-tools.com/`

Which `<a>` links don’t have enough text description?

Take a screenshot of it
</details>

<details>
<summary>29. Sources</summary>

Go to `https://dev-tools.alx-tools.com/`

The `sources` panel allow you to edit files, add breakpoints to analyse your JavaScript code and create snippets.

- Create a new snippet called `allcolors.js`
- Copy-paste the code on [that page](https://github.com/bgrins/devtools-snippets/blob/master/snippets/allcolors/allcolors.js)
- Run the code
- Take a screenshot of the result in your console
</details>

<details>
<summary>30. Block CSS files</summary>

Go to `https://dev-tools.alx-tools.com/`

Block all CSS requests

Take a screenshot of it
</details>

<details>
<summary>31. Application panel</summary>

Go to `https://dev-tools.alx-tools.com/`

The `application` panel gives you access to the storage (cookies, sessions, cache…) and some other options as Services Workers and more recently, notifications.

What is the only key present in the session storage for this page?
</details>

<details>
<summary>32. Service workers</summary>

Go to `https://dev-tools.alx-tools.com/`

Does this page have any service workers? `Yes` or `No`
</details>

<details>
<summary>33. Security</summary>

Go to `https://dev-tools.alx-tools.com/`

The `security` panel allows you to make sure HTTS is properly implement on a webpage.

Which organization issued the SSL certificate for this page?
</details>

<details>
<summary>34. Expiration date</summary>

Go to `https://dev-tools.alx-tools.com/`

When does the SSL certificate expire?

Take a screenshot of it
</details>