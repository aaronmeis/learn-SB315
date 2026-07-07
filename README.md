# Illinois SB 315 • AI Safety Measures Act

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deploy-blue?logo=github)](https://your-username.github.io/learn-SB315)
![License](https://img.shields.io/badge/License-MIT-green.svg)

**Interactive guide to Illinois Senate Bill 315** (Public Act 104-0538) — the landmark 2026 frontier AI safety law.

Signed into law by Governor JB Pritzker on **July 6, 2026**.

> One of the strongest state-level AI regulations in the United States, requiring independent third-party audits for large frontier model developers.

A live demo is available once deployed to GitHub Pages (see badge above).

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
git clone https://github.com/your-username/learn-SB315.git
cd learn-SB315

# Open the page
# On macOS/Linux:
open index.html

# On Windows:
start index.html
```

Or simply drag `index.html` into any browser.

## Deploying to GitHub Pages

This is a static single-file site that works out of the box with GitHub Pages.

### To host your own version

1. Fork this repository on GitHub.

2. Go to your fork's **Settings → Pages**.

3. Under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`

4. Click **Save**.

Your copy will be live at `https://your-username.github.io/learn-SB315`.

> The included `.nojekyll` file prevents GitHub from processing the site with Jekyll.

## Project Structure

```
learn-SB315/
├── index.html          # The complete interactive SPA (single file)
├── README.md
├── LICENSE
├── .gitignore
└── .nojekyll           # For GitHub Pages
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

This is a self-contained single-file project created for learning and reference around Illinois AI policy. The `index.html` is designed to be easy to host anywhere that serves static files.