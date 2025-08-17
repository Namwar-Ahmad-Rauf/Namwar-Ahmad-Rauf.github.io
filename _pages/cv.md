---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 4
redirect_url: https://your-cv-link-here.com # Replace this with your actual CV link
description: Redirecting to CV...
---

<script>
// Immediate redirect to CV
window.location.href = "{{ page.redirect_url }}";
</script>

<div class="text-center mt-5">
  <h3>Redirecting to CV...</h3>
  <p>If you are not redirected automatically, <a href="{{ page.redirect_url }}" target="_blank">click here</a>.</p>
</div>
