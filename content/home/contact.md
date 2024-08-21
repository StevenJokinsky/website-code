---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

align: left
title: Contact Me
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  
design:
  columns: '2'
---
<style>
    .google-maps {
        position: relative;
        padding-bottom: 75%; // This is the aspect ratio
        height: 0;
        overflow: hidden;
    }
    .google-maps iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100% !important;
        height: 100% !important;
    }
</style>

<div class="google-maps">
    <iframe src="https://maps.app.goo.gl/bP4bVDPRnGsdxSSZA" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe></iframe>
</div>
