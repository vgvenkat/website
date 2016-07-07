---
layout: post
title:  "Notes on Text Alignment, Notes-4"
date:   2016-07-06 23:14:00 -0700
categories: notes, text align, vertical horizontal
---
### Text Align property
- use text-align to align text horizontally in a block element
    -  can also be used to align images if they are in an inline-block

For languages from right to left, use `<html dir="rtl" lang="ar">` or use `direction` css to specify `ltr or rtl`.

**Vertical Align**
- use it to align text vertically in same line or in a table cell
- Works only with inline, inline-block elements and table cells
- `vertical-align: super` for superscript and others..
- Use this heavily for math and chemical functions.

**line-height**
- use it to specify minimal heights of inline elements.
- default size is 1.2 times base font size

**Centering content in block elements**
- use `margin: 0 auto`. this will center content if it is block element

Tables have `caption, thead, tbody,` elements. Use tables sparingly as not so good for accessibility and SEO
