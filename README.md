# Bootstrap 6 UI Class Guides & Migration Reference

A standalone, interactive collection of visual subject guides, component demonstrations, and migration references for **Bootstrap 6** (`v6.0.0-alpha.1`).

Each topic is provided as an independent, fully-styled HTML reference with copy-ready snippets, side-by-side demos, and explanations.

---

## 📚 Included Guides

| Guide | File | Highlights |
| :--- | :--- | :--- |
| **Index / Portal** | `index.html` | Navigation hub linking to all topics |
| **Layout & Grid** | `01-layout-grid.html` | Responsive prefixes (`sm:`, `md:`, `lg:`), column wrapping, alignment, gutters |
| **Typography & Tables** | `02-typography-tables.html` | Type scale, headings, table variants, striped columns |
| **Colors & Themes** | `03-colors-themes.html` | Semantic tokens, color schemes, light/dark mode, `theme-*` classes |
| **Interactive Components** | `04-interactive-components.html` | Native Dialogs, Drawers, Menus, Hover-lift, Scrollspy, Avatars |
| **Forms & Spacing** | `05-forms-spacing.html` | Modern form controls, checks/radios, validation states, spacing utilities |
| **OTP Input Examples** | `bootstrap6_otp_input_examples.html` | Multi-digit verification codes, PIN entry, masking, separators |
| **Datepicker Examples** | `bootstrap6_datepicker_examples.html` | Native calendar, date ranges, multi-month pickers, formatting |
| **v5 → v6 Migration** | `bootstrap6_v5_to_v6_migration.html` | Complete checklist of class renames, ESM migration, Sass `@use` changes |
| **AI Support & Agent Tools** | `bootstrap6_ai_support.html` | Machine-readable docs (`llms.txt`), Agent Skills CLI, and anti-hallucination prompt generator |

---

## 🚀 Running Locally

No bundlers, node dependencies, or build pipelines are required. All pages load Bootstrap 6 directly from the official jsDelivr CDN.

### Option 1: Direct File Opening
Double-click `index.html` or open it directly in any modern browser.

### Option 2: Local HTTP Server (Recommended)
Using Python:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000` in your browser.

> **Browser Requirement:** Bootstrap 6 targets modern browsers utilizing native web platform features (`<dialog>`, `:has()`, `container queries`, ESM modules). Recommended: Chrome 130+, Edge 130+, Firefox 132+, or Safari 18+.

---

## 🛠️ Tech Stack & Versioning

- **CSS Framework:** [Bootstrap 6.0.0-alpha.1](https://getbootstrap.com/docs/6.0/) via jsDelivr CDN
- **JavaScript:** Native ES Modules (`type="module"`)
- **Typography:** Inter, Instrument Serif, JetBrains Mono (Google Fonts)
- **Custom Enhancements:** `assets/premium.css` (polished SaaS styling and demo canvas)

---

## 📄 License

Open-source project for educational and reference purposes.
