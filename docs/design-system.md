# GitHub Profile Portfolio — Design System & Visual Specification
**Owner:** Vasudev Gajjela  
**Visual Direction:** Midnight Violet & Electric Violet Dark Developer Aesthetic

---

## 1. Color Palette Tokens

| Token Name | Hex Code | Role in Interface |
| :--- | :--- | :--- |
| **Midnight Violet** | `#190B46` | Deep foundation, canvas background, primary dark fill |
| **Electric Violet** | `#762FF2` | Primary vibrant accent, glowing borders, active highlights |
| **Royal Purple** | `#4C2ACB` | Secondary accent, badge outlines, gradient transitions |
| **Porcelain** | `#F7F7FB` | Primary high-contrast text, major headings |
| **Lavender Mist** | `#E8E6F0` | Subtitles, secondary copy, description text |
| **Deep Ink Surface** | `#120A2E` | Card surface fills, panel backgrounds |
| **Subtle Border** | `#2D1C68` | 1px clean card dividers and container borders |

---

## 2. Typography & Layout Specifications

- **Native Markdown Hierarchy:**
  - `##` Section Titles: Prefixed with consistent themed visual markers (e.g. `## ⚡ Current Focus`, `## 🛠 Technology Stack`, `## 🚀 Flagship Architecture`).
  - Section Dividers: Clean HTML `<hr>` elements styled for GitHub dark/light mode neutrality.
- **SVG & Visual Asset Typography:**
  - Font Stack: `Plus Jakarta Sans, system-ui, -apple-system, Segoe UI, Roboto, sans-serif`
  - Weights: `700` for primary display headings, `500` for subtitles and metric labels.
- **Badge Standardization:**
  - Format: Unified Shields.io badges using flat-square styling with dark violet background (`#190B46`), white logos, and Electric Violet (`#762FF2`) accents.
  - Avoid rainbow or disparate badge designs; maintain visual cohesion across all 6 technical categories.

---

## 3. Directory Layout

```text
GajjelaVasudev/
├── .github/
│   └── workflows/
│       └── profile-3d.yml          # Automated 3D contribution workflow
├── assets/
│   ├── profile-banner.svg          # Premium vector hero banner
│   └── icons/                      # Category and platform vector marks
├── docs/
│   ├── profile-audit.md            # Repository and security audit
│   └── design-system.md            # Visual specifications and token guide
└── README.md                       # The main GitHub profile document
```
