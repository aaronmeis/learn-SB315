# Illinois SB 315 • AI Safety Measures Act

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-blue?logo=github)](https://YOUR-USERNAME.github.io/learn-SB315)
![License](https://img.shields.io/badge/License-MIT-green.svg)

**Interactive guide to Illinois Senate Bill 315** (Public Act 104-0538) — the landmark 2026 frontier AI safety law.

Signed into law by Governor JB Pritzker on **July 6, 2026**.

> One of the strongest state-level AI regulations in the United States, requiring independent third-party audits for large frontier model developers.

**Live Demo**: Deploy this repo to GitHub Pages to view the interactive single-page application.

## Features

- 📜 **Full interactive breakdown** of the law's key provisions
- 🔍 **Searchable + filterable** requirements
- 📅 **Visual legislative timeline**
- ⚖️ **Comparison** with California and New York AI laws
- 🧩 **Role-based explainers** (For AI companies / Public / Policymakers)
- ✅ **Interactive compliance checklist** (saved locally)
- 📱 Fully responsive + dark mode friendly
- 🚀 100% static single-file `index.html` — perfect for GitHub Pages

## Quick Facts

- **Applies to**: Large frontier AI developers (OpenAI, Anthropic, Google DeepMind, xAI, etc.)
- **Landmark requirement**: Annual independent third-party audits of safety practices
- **Incident reporting**: 72 hours (24 hours for imminent harm)
- **Penalties**: Up to $1M per violation, $3M for repeats
- **Effective**: January 1, 2027

## Getting Started Locally

```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/learn-SB315.git
cd learn-SB315

# Open the page
# On macOS/Linux:
open index.html

# On Windows:
start index.html
```

Or simply drag `index.html` into any browser.

## Deploy to GitHub Pages (Recommended)

This project is designed to be deployed directly as a GitHub Pages site:

1. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Illinois SB 315 interactive guide"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/learn-SB315.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repo → **Settings** → **Pages**
   - Under "Build and deployment":
     - Source: **Deploy from a branch**
     - Branch: `main`
     - Folder: `/ (root)`
   - Click **Save**

3. Your site will be live at:
   ```
   https://YOUR-USERNAME.github.io/learn-SB315
   ```

> **Note**: The `.nojekyll` file is included so GitHub Pages serves the site without Jekyll processing.

## Project Structure

```
learn-SB315/
├── index.html          # The complete interactive SPA (single file)
├── README.md
├── LICENSE
├── .gitignore
├── .nojekyll           # For GitHub Pages
└── (optional agent context files)
```

## Sources & References

- [Official Illinois General Assembly – SB 315](https://www.ilga.gov/Legislation/BillStatus?DocNum=315&DocTypeID=SB&GA=104&GAID=18&SessionID=114)
- [Public Act 104-0538](https://www.ilga.gov/legislation/PublicActs/View/104-0538)
- Full bill text PDFs available on ilga.gov
- Additional analysis from WIRED, IAPP, Transparency Coalition, and others

## Contributing

Contributions, corrections, and improvements are welcome!

- Found an inaccuracy in the bill summary? Open an issue or PR.
- Want to add new interactive features? PRs encouraged.

## Disclaimer

This is an **unofficial educational and reference tool**. It is not legal advice. Always consult the official text of Public Act 104-0538 and qualified legal counsel for compliance matters.

---

**Built as a learning project** around Illinois AI policy. The `index.html` is intentionally a self-contained single file for easy deployment.