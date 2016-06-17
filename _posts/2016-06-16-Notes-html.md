---
layout: post
title:  "Notes on HTML, Notes-1"
date:   2016-06-16 21:56:00 -0700
categories: notes, html
---
## DOM
- dom is a tree like structure which browser builds from the HTML elements
- dom is a convention of representation HTML

## Browser
- Everything is a *rectangle*. Shapes are changed by using css.
-  thinking of the web as boxes is easier to build.
- give class names semantic titles

## Style matching
- inline style > html style > external style > browser style.
- Cascading because parent style do apply to children.
- If multiple styles present, the most specific rule is applied.
## HTML outlines and sections
- Tags determine both semantic meaning and also what types of default styles get applied to it.

- Proper grouping of content inside body is needed for assistive technology
- *Div* s sometimes are vague for sectioning
- HTML5 introduces section, article, aside, nav for this purpose.
- aside tag is used for sections that are not related to the main flow of the page, like an ad or explanation box.
- information relating to the whole site are grouped in header, footer, nav.

### Sectioning roots
- Tags that introduce external resource but do not contribute to outline of page, blockquote,details, fieldset, figure
- [More information (moz developer link)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Using_HTML_sections_and_outlines#The_HTML5_Outline_Algorithm)
### Tip
- since different browsers have different default styles, it is popular to use normalize.css to reset css

**Box Model**
- Everything on the webpage is a box

*Always code, test and refine*

- Verify code if it meets w3 standards
To verify HTML: http://validator.w3.org/#validate_by_input
To verify CSS: http://jigsaw.w3.org/css-validator/#validate_by_input
