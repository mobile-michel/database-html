---
title: Sectioning elements
description: ARIA landmarks & other HTML sectioning elements
link: https://www.w3.org/WAI/ARIA/apg/patterns/landmarks/examples/HTML5.html
layout: base
tags: primary
---

## With ARIA landmarks

### `Header`
- default landmark role: `banner` (when in context of the `body` element)
- the `header` element is **not** a `banner` landmark when it is a descendant of the following HTML sectionning elements: `article, aside, main, nav, section`
- content: one or more heading elements, logo or icon, authorship info, search tool

### `Nav`
- default landmark role: `navigation`
- content: main navigation links

### `Main`
- default landmark role: `main`

### `Aside`
- default landmark role: `complementary`

### `Section`
- default landmark role: `region` (when it has an accessible name using `aria-labelledby`, `aria-label` or `title` attribute)
- content: chapters, introduction, news item, contact info

### `Form`
- default landmark role: `form` (when it has an accessible name using `aria-labelledby`, `aria-label` or `title` attribute)

### `Search`
- default landmark role: `search` (use the `search` landmark instead of the `form` landmark when the form is used for search functionality)

### `Footer`
- default landmark role: `contentinfo` (when in context of the `body` element)
- the `footer` element is **not** a `contentinfo` landmark when it is a descendant of the following HTML sectionning elements: `article, aside, main, nav, section`
- content: authorship info, copyright, contact, sitemap, back to top, some links, related documents

[AIRA Landmark Resources](https://www.w3.org/WAI/ARIA/apg/patterns/landmarks/examples/resources.html)

## Others HTML Sectioning Elements

### `Body`
- document body

### `Address`
- contact information for a page or article

### `Article`
- content: forum posts, blog posts, user comments, product cards, newspaper articles
