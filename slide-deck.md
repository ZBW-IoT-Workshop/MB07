---
marp: true
lang: de-CH
title: Marp Template
description: Marp template and example slides
theme: custom
transition: fade
paginate: true
_paginate: false
---

# <!--fit--> Marp Template

Marp template and example slides

<https://github.com/norad32/marp-template>

<style scoped>a { color: #36c; }</style>

<!-- This is presenter note. You can write down notes through HTML comment. -->

---

<!-- _backgroundColor: "#123" -->
<!-- _color: "#fff" -->

## Custom background and text color

This slide shows Marp frontmatter overrides for background and text color.

---

![bg right 60%](assets/img.jpg)

## Right image

- The image is on the right

---

## Blurred image

![bg 40% opacity blur](assets/img.jpg)

---

## Two columns

<div class="two-columns">

### Left column

- Item 1
- Item 2
- Item 3

<p class="break"></p>

### Right column

- Item A
- Item B
- Item C

</div>

---

<!-- _class: small-text -->

## Small text section

This slide uses the `small-text` class on the whole section.

You can use it for denser content, notes, definitions, or comparison slides.

- Smaller overall font size
- Useful for tables or longer bullet lists
- Applied via `<!-- _class: small-text -->`

---

### Created by ([@norad32](https://github.com/norad32))

<https://github.com/norad32/marp-template>
