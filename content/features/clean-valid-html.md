---
author: Leon Stafford
title: Clean, valid HTML
date: "2020-09-15"
categories:
- features
tags:
- xhtml
- validation
---

Accessible Minimalism's theme code [validates](https://validator.w3.org/check?uri=https%3A%2F%2Faccessible-minimalism.netlify.app) against XHTML 1.0 Strict code
 standard, whilst being compatible with HTML 5 standards.

You can optionally use [HTML Tidy](https://www.html-tidy.org/) as we do on this
 website, to cleanly present your source code. We can safely choose not to
 minify our source code, due to its lightweight size. It's also likely to be
 served compressed by the webserver, so keeping the source code easily readable
 by your users is an additional accessibility improvement.
