<!-- marp: true -->
<!-- theme: custom -->
<!-- paginate: true -->

---
title: Product Documentation — Marp Edition
author: 24f2000773@ds.study.iitm.ac.in
---

<!-- class: lead -->
<style>
/* Custom theme CSS for Marp */
:root{
  --primary:#0b5ed7;
  --accent:#0a84ff;
  --bg:#fbfdff;
  --text:#0f1720;
}

section {
  background: var(--bg);
  color: var(--text);
  font-family: "Inter", "Segoe UI", Roboto, Arial, sans-serif;
  padding: 48px;
}

/* Header styles */
h1, h2, h3 { color: var(--primary); margin-bottom: 0.25em; }

/* Footer / page-number area (Marp will render page numbers when paginate is enabled) */
footer {
  color: #556;
  font-size: 0.75rem;
  padding-top: 8px;
}

/* Small utility classes */
.lead { font-size: 1.15rem; }
.small { font-size: 0.9rem; color: #445; }

/* Highlight block for code or callouts */
.callout {
  border-left: 6px solid var(--accent);
  background: rgba(10,132,255,0.05);
  padding: 12px 16px;
  border-radius: 6px;
}
</style>

<!-- Slide 1: Title (includes email) -->
# Product Documentation — Technical Overview
### Maintainable docs with Marp

**Contact:** 24f2000773@ds.study.iitm.ac.in

---

<!-- class: center -->
# Goals
- Source-controlled, Markdown-first documentation  
- Easily convertible to PDF/HTML using Marp CLI or GitHub Actions  
- Reusable theme, consistent typography, and accessible colors

---

<!-- class: invert -->
# System Design Highlights

- Microservices architecture  
- API gateway + event-driven internals  
- Observability, CI/CD, and automated releases

**Complexity (algorithmic example):**

\[
T(n) = O(n \log n) \quad\text{(typical sort/merge-based operations)}
\]

---

<!-- backgroundImage: "https://images.unsplash.com/photo-1508921912186-1d1a45ebb3c1?auto=format&fit=crop&w=1400&q=80" -->
<!-- backgroundSize: cover -->
<!-- backgroundOpacity: 0.35 -->

# Visualizing the Workflow

This slide uses a full-bleed background image to illustrate system flow.

---

<!-- class: callout -->
# Example Configuration (Custom Styling)

Use this block to document theme variables and Marp usage:

```yaml
# marp CLI usage example for conversion
marp --html --theme ./slides.md --allow-local-files slides.md
