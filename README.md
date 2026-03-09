# 📱 Lycamobile – Normal Retailer Incentive Scheme

> **March 2026 Edition** · Multilingual Interactive Incentive Calculator & Programme Guide

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue)](https://hotspot-gif.github.io/std-kb/)

A single-page, multilingual web application that displays the Lycamobile Normal Retailer Incentive Programme for March 2026. Built as a comprehensive knowledge base for authorised retailers and distributors.

---

## 🌐 Live Demo

**[https://hotspot-gif.github.io/std-kb/](https://hotspot-gif.github.io/std-kb/)**

---

## ✨ Features

### 🌍 4 Languages
| Language | Code | Direction |
|----------|------|-----------|
| 🇬🇧 English | `EN` | LTR |
| 🇮🇹 Italian | `IT` | LTR |
| 🇵🇰 Urdu | `UR` | RTL |
| 🇧🇩 Bengali | `BN` | LTR |

Full RTL support for Urdu with proper border, alignment, and layout mirroring.

### 🧮 Interactive Incentive Calculators

Two separate calculators with real-time computation:

**New Activations Calculator**
- Plan selection from all eligible plans (€6.99 – €14.99)
- Activation count with automatic tier detection (1–5, 6–14, 15–34, 35+)
- Auto Recharge cashback toggle
- Instant earnings breakdown

**MNP (Port-In) Calculator**
- Plan type selection (≤€6.99 or >€6.99)
- Port-in count with automatic tier detection
- Source operator selection for GARA Extra Boost (+€40 premium / +€20 others)
- Auto Recharge cashback toggle
- GARA eligibility warning (minimum 15 MNP)
- Detailed incentive breakdown

### 📊 Programme Sections

| Section | Description |
|---------|-------------|
| **Activation Compensation** | Two tier tables — Plans ≤€6.99 and >€6.99 with MNP & New Act. rates across 4 tiers |
| **GARA Extra Boost** | +€40 for premium operators (Iliad, Fastweb, CoopVoce, PosteMobile), +€20 for others |
| **Auto Recharge** | 3-step cashback process — plan value returned as cashback |
| **Reduced Renewal** | Reduced rates when renewal falls below 30% (T1) or 50% (port-in) |
| **Eligible Plans** | Tabbed view of MNP and New Activation plans — National, 5G, International |
| **Terms & Conditions** | 8 detailed terms with colour-coded severity cards |
| **Disclaimer** | Legal monitoring and compliance notice |

---

## 💰 Incentive Rate Summary

### New Activations
| Plan Value | 1–5 | 6–14 | 15–34 | 35+ |
|-----------|-----|------|-------|-----|
| ≤ €6.99 | €3 | €5 | €6 | €7 |
| > €6.99 | €5 | €6 | €7 | €9 |

### MNP (Port-In)
| Plan Value | 1–5 | 6–14 | 15–34 | 35+ |
|-----------|-----|------|-------|-----|
| ≤ €6.99 | €8 | €17 | €20 | €23 |
| > €6.99 | €12 | €27 | €31 | €38 |

### GARA Extra Boost (requires 15+ MNP/month)
| Source Operator | Bonus per MNP |
|----------------|--------------|
| Iliad, Fastweb, CoopVoce, PosteMobile | +€40 |
| Other MNO & MVNO | +€20 |

---

## 🛠️ Tech Stack

- **HTML5** — Single-page application (`index.html`)
- **CSS3** — Custom properties, grid, flexbox, animations, RTL support
- **Vanilla JavaScript** — No frameworks, no dependencies
- **Google Fonts** — Barlow Condensed, DM Sans, DM Mono

### No Build Tools Required
This is a **zero-dependency**, static HTML file. No npm, no bundlers, no build steps.

---

## 📁 Project Structure

```
std-kb/
├── index.html     # Complete single-page application
├── README.md      # This file
├── LICENSE        # MIT License
└── .gitignore     # Git ignore rules
```

---

## 🚀 Deployment

### GitHub Pages

1. Go to **Settings** → **Pages** in your repository
2. Set **Source** to `Deploy from a branch`
3. Select `main` branch and `/ (root)` folder
4. Click **Save**
5. Your site will be live at `https://hotspot-gif.github.io/std-kb/`

### Local Development

Simply open `index.html` in any modern browser:

```bash
# Clone the repository
git clone https://github.com/hotspot-gif/std-kb.git
cd std-kb

# Open directly in browser
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows

# Or use any local server
python3 -m http.server 8080
# Then visit http://localhost:8080
```

---

## 🎨 Design System

| Token | Colour | Usage |
|-------|--------|-------|
| `--navy` | `#21264E` | Primary background, headers |
| `--green` | `#08DC7D` | MNP highlights, CTAs, accents |
| `--blue` | `#245BC1` | New activations, 5G plans |
| `--gold` | `#FFD54F` | GARA boost, cashback, warnings |
| `--red` | `#dc2626` | Penalties, deductions |

**Typography:**
- **Barlow Condensed** — Headings, numbers, badges (800–900 weight)
- **DM Sans** — Body text (300–600 weight)
- **DM Mono** — Labels, tags, code-style elements

---

## 📱 Responsive Design

Fully responsive with breakpoints:
- **Desktop** (>700px) — Multi-column grid layouts
- **Mobile** (≤700px) — Single-column stacked layout, adjusted font sizes

---

## 🤝 Distributed By

**Universal Service 2006 S.R.L**  
Via Genzano 195, 00179 Roma  
P.IVA: IT 09037721009

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## ⚠️ Disclaimer

This is an internal knowledge base tool for authorised Lycamobile retailers. The incentive rates, terms, and conditions displayed are subject to change. Lycamobile reserves the right to modify the programme at any time. Always refer to official communications for the most current information.

---

<p align="center">
  <sub>© 2026 Lycamobile. All rights reserved.</sub>
</p>
