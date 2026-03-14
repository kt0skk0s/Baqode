# Baqode — Web & Mobile Development

> Premium design & development studio based in Paralimni, Cyprus.  
> We build elegant Web and Mobile products that matter.

---

## 📁 Project Structure

```
baqode/
├── index.html        # Home page
├── services.html     # Expertise & services
├── work.html         # Portfolio / selected projects
├── about.html        # About the studio
├── contact.html      # Contact form (Formspree)
├── style.css         # Global styles
├── script.js         # JS (nav, animations, cookie consent)
├── logo.png          # Brand logo
├── sitemap.xml       # SEO sitemap
├── robots.txt        # Search engine directives
└── README.md         # This file
```

---

## 🚀 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom, no framework) |
| Scripts | Vanilla JavaScript |
| Fonts | Syne + DM Sans (Google Fonts) |
| Forms | Formspree |
| Hosting | GitHub Pages |

---

## ✨ Features

- Fully responsive (mobile, tablet, desktop)
- Full-screen animated navigation menu
- Smooth page transition (fade in/out)
- Scroll reveal animations
- Bento grid layout (services)
- Featured + grid portfolio layout
- FAQ accordion
- Contact form via Formspree
- Cookie consent banner (GDPR)
- SEO optimised (meta, Open Graph, JSON-LD, sitemap)

---

## 🛠️ Local Development

No build tools required. Just open with a local server:

```bash
# Option 1 — VS Code Live Server extension (recommended)
# Right-click index.html → "Open with Live Server"

# Option 2 — Python
python -m http.server 5500

# Option 3 — Node.js
npx serve .
```

Then visit `http://localhost:5500`

---

## 📬 Contact Form

The contact form uses **Formspree** (`https://formspree.io`).  
Submissions are sent directly to `infobaqode@gmail.com`.  
No backend required.

---

## 🔍 SEO

- Unique `<title>` and `<meta name="description">` per page
- Open Graph + Twitter Card tags
- JSON-LD structured data (index.html)
- `sitemap.xml` — submit to Google Search Console after deploy
- `robots.txt` — allows all crawlers

**After deploying**, update all `https://baqode.com` references with the real domain in:
- `sitemap.xml`
- All `<link rel="canonical">` tags
- All `og:url` meta tags
- JSON-LD `url` field in `index.html`

---

## 🍪 Cookie Consent

A GDPR-compliant cookie banner is included.  
It uses a simple browser cookie (no tracking) to remember the user's choice:
- **Accept** → stores consent for 365 days
- **Decline** → stores refusal for 30 days

No analytics or third-party tracking is currently active.

---

## 📄 License

© 2026 Baqode Studio. All rights reserved.
