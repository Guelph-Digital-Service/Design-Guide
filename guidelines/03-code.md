---
layout: page
group: guidelines
permalink: /guidelines/code.html
title: Code conventions
description: Guidelines for the City of Guelph's code base.
---

> Every line of code should appear to be written by a single person, no matter the number of contributors.

Enforce these agreed upon coding conventions and standards at all times. Small or large, call out what's incorrect - it's the only way we can all stay simpatico. These code conventions relate primarily to our usage of HTML, CSS, Javascript, and Markdown - but you should keep coding conventions in mind when working with our PHP, C++, or MySQL codebases. We currently utilize the CodeGuide.co guide for HTML & CSS development, and you should too!

[Check out the Code Guide](https://codeguide.co/){: .c-btn}
{: .txtcenter}

## HTML
> "HTML is the unifying language of the World Wide Web. Using just the simple tags it contains, the human race has created an astoundingly diverse network of hyperlinked documents, from Amazon, eBay, and Wikipedia, to personal blogs and websites dedicated to cats that look like Hitler" - @adactio

HTML5 is the version we use, but HTML versions don't really matter. Browsers understand the tags they support, regardless of the doctype / version we validate against. HTML gives meaning to content so that browsers and devices can then give that meaning to a user. e.g.
- Headings `h1` to `h5` form a document outline and can give a table of contents for easy navigation.
- A screen reader gets to a `<table>` and explains to a blind user how to navigate its content by rows/columns.
- When a user clicks on a `<label for="email">` the associated input control gains focus `<input id="email">`

If it's a heading use a heading. If it's tabular data use a table. If it's a list of links then make it so.

TLDR: HTML IS FOR STRUCTURE NOT FOR STYLE!


## CSS


- Keep CSS completely separate from the HTML
- Re-use specific modules e.g. reset, grid, forms, type, print
- use shorthand syntax wherever possible
- use lower-case-hyphenated .class-names and #ids
- code to a standards compliant browser first, then fix issues in IE
- Use meaningful class names and IDs - e.g. "loading" as opposed to "bigYellowSpinnyThing"
- Control the margin and padding on all the elements you use.
- Avoid absolute positioning
- Avoid !important
- Don't suffer from [divitus and classitus](http://blog.semanticsworks.com/2009/04/divitus-classitus_8466.html)
- Don't use breaks `<br>` just to make space in your layout
- Avoid hacks unless there is no other way to achieve what you want
