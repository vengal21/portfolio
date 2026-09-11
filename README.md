# Vengal Rao P — Portfolio Website

> **Live site:** [vengalraop.github.io](https://vengalraop.github.io)  
> **Role:** Business Analyst | CRM & RPA Automation | Power BI | SQL | ETL | Forecasting  
> **Status:** Open to BA · DA · BI Analyst roles — Chennai · Bengaluru · Hyderabad · Remote

---

## About This Project

This is my personal portfolio website — a single-page HTML file built to professionally present my work experience, projects, skills, and impact metrics as a Business Analyst in the automotive CRM and data analytics domain.

The site is fully self-contained (one `.html` file, no build tools, no dependencies beyond Google Fonts) and is hosted for free on GitHub Pages.

---

## What's Inside

```
vengalraop.github.io/
│
└── index.html          # Complete portfolio — all sections in one file
```

### Sections

| Section | Description |
|---|---|
| **Hero** | Role, positioning statement, open-to-work status, client brands |
| **Metrics** | 4 key impact numbers with animated counters and sequential color bars |
| **Projects** | 6 professional projects with impact badges and tech stacks |
| **Experience** | Career timeline — WyzMindz Solutions, DataPrompt International, SJCE |
| **Skills** | 5 categorized skill groups with qualitative color grading |
| **Clients** | 7 automotive brands served across dealership CRM implementations |
| **Contact** | Email and LinkedIn — resume download link |

---

## Color System

The color grading follows a structured 4-grade data visualization system:

| Grade | Applied To | Purpose |
|---|---|---|
| **Sequential** | Metrics strip (bar + number color) | Single blue hue `#C5D3F0 → #1A3272`, higher value = deeper shade |
| **Semantic / Alert** | Project impact badges | Forest green `#4D8B65` for positive outcomes, amber `#C8860A` for process metrics |
| **Qualitative** | Skill category pills | 5 distinct muted hues at equal visual weight — slate-blue, teal, plum, amber, steel-blue |
| **60-30-10 Canvas** | Entire layout | `#F8F9FA` surfaces · `#212529` charcoal type · `#4361A8` action hue for CTAs only |

---

## Tech Stack

| Layer | Choice | Reason |
|---|---|---|
| Markup | HTML5 | Single file, zero dependencies |
| Styling | Vanilla CSS with CSS custom properties | Full color system in `:root` variables, easy to update |
| Fonts | Google Fonts — DM Sans + Inter | Free, fast CDN, professional pairing |
| Hosting | GitHub Pages | Free, custom domain supported, HTTPS by default |
| Animation | Vanilla JS IntersectionObserver | Counter animation on metrics — no library needed |

No React. No Node. No build step. Open `index.html` in a browser and it works.

---

## How to Run Locally

```bash
# Clone the repo
git clone https://github.com/vengalraop/vengalraop.github.io.git

# Open in browser — no server needed
open index.html

# Or use VS Code Live Server extension for auto-refresh on edit
```

---

## How to Deploy on GitHub Pages

```bash
# Step 1: Create a repo named exactly: yourusername.github.io
# Example: vengalraop.github.io

# Step 2: Clone it
git clone https://github.com/vengalraop/vengalraop.github.io.git

# Step 3: Copy index.html into the repo folder
cp index.html vengalraop.github.io/

# Step 4: Commit and push
cd vengalraop.github.io
git add .
git commit -m "Add portfolio"
git push origin main

# Step 5: Enable GitHub Pages
# GitHub repo → Settings → Pages → Source: Deploy from branch → main → / (root)
# Your site goes live at: https://vengalraop.github.io
```

Live in under 2 minutes. No configuration required.

---

## Resume Link Setup

The three "Download Resume" buttons in the site link to a Google Drive PDF.
To activate them after cloning:

1. Upload `Vengal_Rao_Resume_1Page.pdf` to Google Drive
2. Right-click → **Share** → Anyone with the link → **Viewer**
3. Copy the file ID from the URL:
   ```
   https://drive.google.com/file/d/THIS_IS_YOUR_FILE_ID/view
   ```
4. In `index.html`, find and replace all 3 instances of:
   ```
   YOUR_RESUME_FILE_ID
   ```
   with your actual file ID

---

## Customization

All colors are defined as CSS custom properties in `:root` at the top of `index.html`. To update any color:

```css
:root {
  --action:    #4361A8;   /* 10% action hue — buttons, links, CTAs */
  --sem-green: #4D8B65;   /* semantic green — positive outcomes */
  --sem-amber: #C8860A;   /* semantic amber — process metrics */
  --cat-1:     #4361A8;   /* qualitative cat-1 — Analytics & BI */
  --cat-2:     #2E7D6E;   /* qualitative cat-2 — ETL & Automation */
  /* ... */
}
```

To update personal details, search and replace:
- `vengalraoofficial@gmail.com` → your email
- `linkedin.com/in/vengalraop` → your LinkedIn URL
- `YOUR_RESUME_FILE_ID` → your Google Drive file ID

---

## Project Highlights Featured

| Project | Key Outcome |
|---|---|
| RPA Data Extraction Pipeline | 50% reduction in data collection time |
| Service & Insurance Forecasting Model | 50% → 95% accuracy · 80% less manual effort |
| Mahindra Dealer — CRM Implementation | 30% improvement in data consistency |
| Hyundai Dealer — Workflow Optimization | 100% UAT coverage · 20% efficiency gain |
| Dealer Group — Reporting Optimization | 40% less manual reporting · 30% faster SQL |
| SMS/Email Spam Detection — NLP | Final year ML project using Naive Bayes + TF-IDF |

---

## Certifications

- Master Program in Data Science — **LIVEWIRE**
- Data Analytics & Visualization Job Simulation — **Accenture (Forage)**
- Data Visualisation: Empowering Business with Effective Insights — **TATA Group (Forage)**
- Microsoft Azure Fundamentals AZ-900 — **In Progress**

---

## Contact

- **Email:** vengalraoofficial@gmail.com
- **LinkedIn:** [linkedin.com/in/vengalraop](https://www.linkedin.com/in/vengalraop)
- **Location:** Bengaluru, India — open to Chennai, Hyderabad, Remote

---

*Built with vanilla HTML, CSS, and JS. No frameworks. No build tools. Just a file.*