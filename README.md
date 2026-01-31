# Github_docs

Documentation and landing site for FlowMint products. Host on GitHub Pages for store discovery and user documentation.

## Contents

- **index.html** — Landing page with **FlowMint Recorder** and **FlowMint Test Evidence** product cards, About, and Contact. Use for Google and store discovery.
- **FlowMint_Recorder/user-guide.html** — Full user guide for **FlowMint Recorder** (record, assertions, data-driven, export, suites, playback, settings).
- **FlowMint_Test_Evidence/user-guide.html** — Full user guide for **FlowMint Test Evidence** (record with screenshots, report, export PDF/HTML/JSON, sessions, settings).
- **privacy.html** — Privacy policy page. Link from store listings or footer.

## How to host on GitHub

See **[HOSTING.md](HOSTING.md)** for step-by-step instructions: push repo to GitHub, enable Pages from the docs folder (or root with `/docs`), get your URL, and update links.

## Enable GitHub Pages (quick)

1. In your repo: **Settings** → **Pages**.
2. **Source:** Deploy from a branch.
3. **Branch:** main (or your default) → **/** (root) or **/docs** depending on where this folder lives — then **Save**.
4. Your site will be at `https://<username>.github.io/<repo-name>/`.

## Before publishing

- In **index.html**, replace placeholder URLs:
  - `og:url` and `canonical` — your GitHub Pages URL.
  - `og:image` — full URL to your icon (e.g. raw GitHub URL to an icon image).
  - “Get Recorder” / “Get Test Evidence” — your Chrome Web Store (or Edge/Firefox) extension URLs once published.
- Ensure **FlowMint_Recorder** and **FlowMint_Test_Evidence** folders (with `user-guide.html`) are deployed so the User Guide links work.

## SEO

- **Meta title & description** — What shows in Google results (index and user guides).
- **Meta keywords** — Terms people search for (record browser tests, export Playwright, test evidence, screenshots, QA, etc.).
- **Open Graph** — Better previews when links are shared (Twitter, LinkedIn).
- **Canonical URL** — Tells search engines the main URL for each page.
- **Structured content** — H1 and product sections with key phrases so the site ranks for relevant searches.
