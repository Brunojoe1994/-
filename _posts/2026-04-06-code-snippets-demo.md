---
layout: post
title: "Working with Code Snippets in Jekyll"
date: 2026-04-06
categories:
  - jekyll
  - tutorials
tags:
  - code
  - snippets
  - liquid
  - markdown
triggers:
  - theme-update
  - blog-feature
badges:
  enabled: true
hero:
  enabled: true
  style: "info"
  message: "Learn how to use code snippets in Jekyll!"
sidebar: dynamic-sidebar.html
permalink: /blog/jekyll-code-snippets/
---

## Code Snippet Examples in Jekyll

Jekyll makes it easy to include syntax‑highlighted code blocks.  
Below are examples for **Liquid**, **YAML**, **HTML**, **CSS**, and **JavaScript**.

---

## ✅ Liquid Example

```liquid
{% if page.triggers contains "blog-feature" %}
  <p>The blog feature is enabled!</p>
{% endif %}
