---
title: Page Regions
description: page regions in page structure tutorial
link: https://www.w3.org/WAI/tutorials/page-structure/regions/
layout: base
tags: primary
---
`<body>`
- `<header role="banner">`
- `<nav role="navigation" aria-label="Main">`
- `<main role="main">`
  - `<article>`
    - `<nav aria-label="Contents">`
    - `<aside role="complementary" aria-labelledby="Related">`
  - `<aside role="complementary" aria-labelledby="Latest News">`
- `<footer role="contentinfo">`

`</body>`


`<body>`
- `<header role="banner">`
- `<nav role="navigation" aria-labelledby="mainnavheader">`
- `<main role="main">`
  - `<article>`
    - `<nav aria-labelledby="tocheader">`
    - `<aside role="complementary" aria-labelledby="relatedheader">`
  - `<aside role="complementary" aria-labelledby="latestheader">`
- `<footer role="contentinfo">`

`</body>`