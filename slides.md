<!-- marp: true -->
<!-- theme: custom-theme -->
<!-- paginate: true -->

---
title: Product Documentation Presentation
author: 24f2000773@ds.study.iitm.ac.in
---

<!-- class: lead -->

<style>
:root {
  --primary-color: #0055aa;
  --accent-color: #0a84ff;
  --bg-soft: #f4f8ff;
}

section {
  background-color: var(--bg-soft);
  font-family: "Segoe UI", sans-serif;
}

h1, h2, h3 {
  color: var(--primary-color);
}
</style>

# Product Documentation  
### Technical Overview

**Email:** 24f2000773@ds.study.iitm.ac.in

---

<!-- class: invert -->

# System Architecture

- API Gateway  
- Microservices  
- Distributed events  

Mathematical complexity:

\[
T(n) = O(n \log n)
\]

---

<!-- backgroundImage: "https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=1400&q=60" -->
<!-- backgroundSize: cover -->

# Platform Workflow

Steps:

1. Request enters gateway  
2. Service routing  
3. Response aggregation  

---

<!-- class: highlight -->

# Custom Styling Demonstration

This slide uses a custom class directive.

```css
section {
  border-left: 10px solid var(--accent-color);
  padding-left: 24px;
}
