---
marp: true
theme: custom
paginate: true
class: lead
style: |
  /* Custom Marp theme */
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap');

  :root{
    --bg: #0f172a;
    --surface: #0b1220;
    --accent: #7c3aed;
    --primary: #06b6d4;
    --muted: #9fb6b5;
    --text: #e6eef8;
  }

  section {
    font-family: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    background-color: var(--surface);
    color: var(--text);
    padding: 48px;
  }

  /* Headings */
  h1 { color: var(--primary); font-size: 2.6rem; letter-spacing: -0.02em; }
  h2 { color: var(--accent); font-size: 1.8rem; }

  /* Small email block */
  .email { color: #c7f9f8; font-weight: 600; font-size: 0.95rem; }

  /* Code blocks */
  pre, code { background: rgba(255,255,255,0.03); border-radius: 6px; padding: .35rem .5rem; }

  /* Footer / page number area (works together with paginate: true) */
  .marp-footer { position: fixed; bottom: 14px; right: 18px; color: var(--muted); font-size: 0.82rem; }

  /* Slide-specific helper classes */
  .two-col { display: flex; gap: 28px; align-items: flex-start; }
  .two-col > div { flex: 1; }

  /* Accent pills */
  .pill { display:inline-block; padding:6px 10px; border-radius:999px; background: rgba(124,58,237,0.14); color:var(--accent); font-weight:700; }

  /* Accessibility: high contrast for images with text */
  .bg-caption { background: rgba(0,0,0,0.45); padding: 8px 12px; border-radius: 6px; display:inline-block; }

---

<!-- _class: lead -->
# Product Documentation — **Lockdown CLI Sync**
_A concise, version-controlled Marp deck for technical documentation_

<span class="email">Contact: 24f2000773@ds.study.iitm.ac.in</span>

<footer class="marp-footer">Product Docs • v1.0 • 24f2000773@ds.study.iitm.ac.in</footer>

---

## Why Marp for product docs?

- Markdown-first: maintainable in Git & easy code review  
- Exportable: HTML, PDF, PPTX via Marp CLI / GitHub Actions  
- Lightweight theming & slide-level directives for customization

---

## Repo layout (recommended)

```text
/README.md
/slides.md            <- This Marp file
/assets/
  /img/
  /diagrams/
/docs/
  /api.md
  /cli.md
.github/workflows/md-to-pdf.yml
