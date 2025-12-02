---
marp: true
theme: custom-theme
paginate: true
_paginate: false
title: "Product Documentation Presentation"
description: "Marp-based documentation"
class: lead
---

<!--
Contact: 24f2000773@ds.study.iitm.ac.in
-->

# Product Documentation  
### Using Marp for Maintainable Technical Docs

---

<!-- Custom theme -->
<style>
section {
  font-family: "Segoe UI", sans-serif;
}
h1 {
  color: #1976d2;
  font-weight: 700;
}
h2 {
  color: #0d47a1;
}
p {
  font-size: 1.1em;
}
footer {
  color: #444;
  font-size: 0.75em;
}
</style>

<!-- Custom theme definition -->
<!-- You can place this in a separate CSS file if needed -->
<style scoped>
:root {
  --bg-color: #fafafa;
  --fg-color: #111;
}
section {
  background-color: var(--bg-color);
  color: var(--fg-color);
}
</style>

# Why Use Marp for Product Documentation?

- Version-controlled Markdown  
- Easy PDF/HTML export  
- Supports code, math, images  
- Great for engineering + PM teams

---

# Algorithmic Complexity Example

We frequently document engineering decisions using math.

**Time complexity of merge sort:**

\[
T(n) = 2T\left(\frac{n}{2}\right) + O(n)
\]

By Master Theorem:

\[
T(n) = O(n \log n)
\]

---

<!-- Slide with background image -->
<!-- Using a free background URL for demo -->
---
backgroundImage: "https://images.unsplash.com/photo-1527443224154-9f2fc6f74c95?auto=format&fit=crop&w=1200&q=60"
backgroundSize: cover
color: white
---

# System Architecture Overview

The diagram illustrates request flow, caching, and scaling strategies.

*(This slide uses a full-screen background image.)*

---

# Custom-Styled Feature Summary

<div style="border: 2px solid #1976d2; padding: 16px; border-radius: 10px; background: #e3f2fd;">
  
### Key Platform Features
- Modular microservices  
- API-first design  
- Automated testing  
- Observability baked in  
- CI/CD integration

</div>

---

# Contact

For documentation updates or engineering review:

**Email:** 24f2000773@ds.study.iitm.ac.in

Thank you!

