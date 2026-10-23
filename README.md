# Visit Sierra Leone — Modern Ecotourism & Heritage Portal

A unified, multi-page web application project for **Visit Sierra Leone**, crafted in the **Verdant Coast Heritage** design system (combining _Manrope_ typography, _Manrope_ interface geometry, and deep coastal emerald and mint tones).

---

## 📁 Project Structure

All pages and assets are organized in this single project root for seamless local browsing, GitHub Pages hosting, or static site deployment:

```text
visitsalone/
├── index.html                  # Home: Hero, Experience categories, Top curator picks & trip planning
├── about.html                  # About: Geography, 400km coastline, historic sites & responsible travel
├── services.html               # Services: 6 service categories, signature journeys & direct inquiry drawer
├── destinations.html           # Featured Destinations Directory: Hub listing all key reserves & beaches
├── destination-details.html    # Destination: River No. 2 Beach showcase, local photos & activities
├── river2.html                 # Destination: Direct River No. 2 Beach details page
├── banana.html                 # Destination: Banana Island archipelago, snorkeling, ruins & photo gallery
├── tiwai.html                  # Destination: Tiwai Island Wildlife Sanctuary, primates & Moa River cruises
├── contact.html                # Contact: Visitor concierge desk, interactive quick-fill inquiry form & FAQs
├── img/                        # High-resolution local destination photography
├── DESIGN.md                   # Full Design System Specification & Token Reference
└── README.md                   # Project documentation and guide
```

---

## 🧭 Page Overview & Navigation Map

| Page | File | Description | Active Features |
| :--- | :--- | :--- | :--- |
| **Home** | [`index.html`](file:///c:/Users/HP/Documents/bintu/bintu%20Assignment/visitsalone/index.html) | Main portal with search bar, experience pills, and featured cards | Search filter micro-interaction, category anchor jumps |
| **About** | [`about.html`](file:///c:/Users/HP/Documents/bintu/bintu%20Assignment/visitsalone/about.html) | National heritage, Bunce Island memorial, biodiversity stats | Breadcrumbs, key metric chips, conservation principles |
| **Services** | [`services.html`](file:///c:/Users/HP/Documents/bintu/bintu%20Assignment/visitsalone/services.html) | Accommodation, operators, guides, transport, activities | Interactive inquiry modal drawer with party size & date |
| **Destinations Hub** | [`destinations.html`](file:///c:/Users/HP/Documents/bintu/bintu%20Assignment/visitsalone/destinations.html) | Comprehensive destinations directory showcasing all 3 locations | Filtered grid, status chips, quick links |
| **River No. 2 Beach** | [`destination-details.html`](file:///c:/Users/HP/Documents/bintu/bintu%20Assignment/visitsalone/destination-details.html) / [`river2.html`](file:///c:/Users/HP/Documents/bintu/bintu%20Assignment/visitsalone/river2.html) | In-depth guide to River No. 2 Beach & Western Area Peninsula | Authentic photo gallery, quick-fact metric pills, related spots |
| **Banana Island** | [`banana.html`](file:///c:/Users/HP/Documents/bintu/bintu%20Assignment/visitsalone/banana.html) | In-depth guide to Banana Islands (Dublin, Ricketts, Mes-Meheux) | Local photo gallery, snorkeling guides, historic ruins info |
| **Tiwai Island** | [`tiwai.html`](file:///c:/Users/HP/Documents/bintu/bintu%20Assignment/visitsalone/tiwai.html) | In-depth guide to Tiwai Island Wildlife Sanctuary & Moa River | Primate tracking, river safari tours, tented camp booking |
| **Contact** | [`contact.html`](file:///c:/Users/HP/Documents/bintu/bintu%20Assignment/visitsalone/contact.html) | Visitor liaison desk, headquarters contact, and FAQs | Subject quick-fill chips, submit status feedback, expandable FAQs |

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
