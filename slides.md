---
marp: true
theme: custom-theme
paginate: true
title: "Product Documentation Presentation"
description: "Marp-based documentation"
---

<!-- Contact: 24f2000773@ds.study.iitm.ac.in -->

<!-- Global custom theme -->
<style>
/* Basic theme variables */
:root {
  --primary: #1976d2;
  --accent: #0d47a1;
  --muted: #666;
  --slide-bg: #ffffff;
}

/* Slide-level styling */
section {
  background-color: var(--slide-bg);
  color: #111;
  font-family: "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
}

/* Title styling */
h1 { color: var(--primary); font-weight: 700; }
h2 { color: var(--accent); }

/* Page number style (bottom-right) */
footer {
  font-size: 0.85em;
  color: var(--muted);
}

/* A boxed callout style */
.callout {
  border-left: 6px solid var(--primary);
  padding: 12px;
  background: rgba(25,118,210,0.05);
  border-radius: 6px;
}
</style>

<!-- Custom theme directives for Marp -->
<!-- You can also extract these styles into a separate CSS file and point theme: to it -->
---

# Product Documentation  
### Using Marp for Maintainable Technical Docs

---

# Why Marp for Docs?

- Version-controlled Markdown  
- Easy export to PDF/HTML/Slides  
- Supports code, diagrams, math, images

---

# Algorithmic Complexity (Example)

We document algorithmic complexity in-line.

\[
T(n) = 2T\!\left(\frac{n}{2}\right) + O(n)
\]

By the Master Theorem:

\[
T(n)=O(n\log n)
\]

---

---
backgroundImage: "https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1350&q=80"
backgroundSize: cover
backgroundColor: "#000000"
class: lead
---

# System Architecture

This slide uses a **full-screen background image** defined in slide front-matter.

> Contact: 24f2000773@ds.study.iitm.ac.in

---

# Feature Summary

<div class="callout">

**Key Platform Features**
- Microservice modularity  
- API-first design  
- Observability + telemetry  
- CI/CD and automated QA

</div>

---

# Performance Notes

- Average response time: **< 120 ms**  
- SLA target: **99.95%**

---

# Example Pseudocode & Complexity

```text
function mergeSort(arr):
    if length(arr) <= 1:
        return arr
    left, right = split(arr)
    return merge(mergeSort(left), mergeSort(right))
