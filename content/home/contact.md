---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: 'Contact <i class="fas fa-feather-alt"  style="color: #228B22"></i>'
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: formspree
    formspree:
      id: "https://formspree.io/f/xoqydazl"
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

design:
  columns: "2"
  background:
    image: usgs-Eu2uXqoHenE-unsplash.jpg
    image_darken: 0.4
    image_parallax: true
    image_position: center
    image_size: cover
    text_color_light: true
  spacing:
    padding: ["20px", "0", "20px", "0"]
---

