---
title: Markdown
subtitle: Markdown Markup Language

# Summary for listings and search engines
summary: A post about a lightweight markup language

# Link this post with a project
projects: []

# Date published
date: '2022-05-11T00:00:00Z'

# Date updated
lastmod: '2022-05-12T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Academic 
categories:
  - Demo
---

## Overview

Markdown is a lightweight markup language designed to indicate formatting in plain text while maintaining human readability as much as possible, and suitable for machine translation into advanced publishing languages. Originally created in 2004 by John Gruber and Aaron Schwartz. Many language ideas have been borrowed from existing text markup conventions in emails.
Markdown language implementations convert Markdown text into valid, correctly constructed XHTML and replace left angle brackets ("<") and ampersands ("&") with the corresponding object codes. The first implementation of Markdown was a Perl implementation written by Gruber, but after a while many implementations from third-party developers appeared (see below). The Perl implementation is distributed under a BSD type license. Markdown implementations in various programming languages are included (or available as a plugin) in many content management systems.
You can use any text editor to write Markdown, but we recommend Visual Studio Code with the Docs Authoring Pack extension. The Doc Authoring Pack extension contains editing tools and preview functions that allow you to see how the articles on the Documentation site will look like.
Alerts are a special Markdown extension that is used to create citation blocks displayed on the documentation site using colors and icons indicating the importance of the content.

Avoid using the "Note", "Advice", "Important!". Readers often miss them. It is recommended to place their information directly in the text of the article.

If you need to use alerts, limit yourself to one or two per article. Several notes should never be in an article next to each other.
If angle brackets are used in the text of the file (for example, to indicate a placeholder), they need to be encoded manually. Otherwise, Markdown markup considers them HTML tags.

Angle brackets do not have to be escaped in text formatted as embedded code or in code blocks.
Although Markdown supports embedded HTML code, HTML is not recommended for publishing Documentation on the site. Any code, except for a limited list of values, will cause errors and warnings to appear during assembly.
