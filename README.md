# Visit Sierra Leone — Modern Ecotourism & Heritage Portal

A unified, multi-page web application project for **Visit Sierra Leone**, crafted in the **Verdant Coast Heritage** design system (combining _Manrope_ typography, _Manrope_ interface geometry, and deep coastal emerald and mint tones).

---

## 📁 Project Structure

All pages and assets are organized in this single project root for seamless local browsing, GitHub Pages hosting, or static site deployment:

```text
stitch_modern_green_ui_system/
├── index.html                  # Home: Hero, Experience categories, Top curator picks & trip planning
├── about.html                  # About: Geography, 400km coastline, historic sites & responsible travel
├── services.html               # Services: 6 service categories, signature journeys & direct inquiry drawer
├── destination-details.html    # Destination: River No. 2 Beach showcase, gallery, quick stats & activities
├── destinations.html           # Destination alias / quick redirect to destination-details.html
├── contact.html                # Contact: Visitor concierge desk, interactive quick-fill inquiry form & FAQs
├── DESIGN.md                   # Full Design System Specification & Token Reference
└── README.md                   # Project documentation and guide
```

---

## 🧭 Page Overview & Navigation Map

| Page            | File                                                                                                                                             | Description                                                       | Active Features                                                   |
| :-------------- | :----------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------- | :---------------------------------------------------------------- |
| **Home**        | [`index.html`](file:///c:/Users/HP/Downloads/stitch_modern_green_ui_system/stitch_modern_green_ui_system/index.html)                             | Main portal with search bar, experience pills, and featured cards | Search filter micro-interaction, category anchor jumps            |
| **About**       | [`about.html`](file:///c:/Users/HP/Downloads/stitch_modern_green_ui_system/stitch_modern_green_ui_system/about.html)                             | National heritage, Bunce Island memorial, biodiversity stats      | Breadcrumbs, key metric chips, conservation principles            |
| **Services**    | [`services.html`](file:///c:/Users/HP/Downloads/stitch_modern_green_ui_system/stitch_modern_green_ui_system/services.html)                       | Accommodation, operators, guides, transport, activities           | Interactive inquiry modal drawer with party size & date           |
| **Destination** | [`destination-details.html`](file:///c:/Users/HP/Downloads/stitch_modern_green_ui_system/stitch_modern_green_ui_system/destination-details.html) | In-depth guide to River No. 2 Beach & Western Area Peninsula      | Full photo gallery, quick-fact metric pills, related spots        |
| **Contact**     | [`contact.html`](file:///c:/Users/HP/Downloads/stitch_modern_green_ui_system/stitch_modern_green_ui_system/contact.html)                         | Visitor liaison desk, headquarters contact, and FAQs              | Subject quick-fill chips, submit status feedback, expandable FAQs |

---

## 🎨 Design System: Verdant Coast Heritage

- **Typography**:
  - Headings & Editorial Titles: [`Manrope`](https://fonts.google.com/specimen/EB+Garamond) (serif)
  - UI Labels & Narrative Body: [`Manrope`](https://fonts.google.com/specimen/Manrope) (sans-serif)
  - Icons: Google Material Symbols Outlined
- **Color Palette**:
  - `primary`: `#00652c` (Deep coastal forest emerald)
  - `primary-container`: `#15803d` (Vibrant vegetation green)
  - `secondary-container`: `#77f7c4` (Luminous ocean mint)
  - `tertiary`: `#8c4033` (Warm earthen sundown)
  - `background` / `surface`: `#f8faf8` (Soft organic paper white)
  - `inverse-surface`: `#2e3130` (Charcoal forest black footer canvas)
- **Zero-Elevation / Pure Tonal Layering**: Clean borderless containers relying on geometric contrast and pill radius styling (`rounded-full`, `rounded-[22px]`, `rounded-[32px]`).

---

## 🚀 How to Run & Preview

### Option 1: Direct in Any Web Browser

Double-click [`index.html`](file:///c:/Users/HP/Downloads/stitch_modern_green_ui_system/stitch_modern_green_ui_system/index.html) or open it with your browser (Chrome, Edge, Safari, Firefox). All styling is powered by Tailwind CSS CDN and Google Fonts, so no build tools or package managers are required.

### Option 2: Local HTTP Server (Optional)

If you prefer running via a local web server:

```bash
# Using Python
python -m http.server 8000

# Using Node / npx
npx serve .
```

Then visit `http://localhost:8000` in your browser.
