---
title: ARIA example
description: page regions in page structure tutorial
link: https://www.w3.org/WAI/tutorials/page-structure/regions/
layout: default
tags: primary
date: 2024-01-06
---
`<body>`
- `<header>` -> Banner role
- `<nav aria-label="Primary">` -> Primary (Navigation)
- `<form role="search">`  -> Search
- `<main>` -> Main role
  - `<aside aria-labelledby="latestNews">` -> Latest news (Complementary)
    - `<h3 id="LatestNews">Latest News</h3>`
    - `<nav aria-label="Secondary">` -> Secondary (Navigation)
  - `<section aria-labelledby="documentation">` -> Documentation (Region)
    - `<h1 id="documentation">Documentation</h1>`
- `<footer>` -> Contentinfo role
  - `<form aria-labelledby="newsletter-subscribe-form">` -> Subscribe (Form)
  - `<nav aria-label="Footer">` -> Footer (Navigation)
`</body>`