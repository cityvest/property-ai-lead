# 🏢 Property Lead Dashboard

A mobile-first dashboard for property agents to track buyer criteria and log agent reports. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no build tools.

## Features

- **Buyer Criteria** — Log buyer name, budget, property type, location and notes
- **Agent Reports** — Track leads, conversions, and weekly notes per agent
- **Live Stats** — Instant summary cards for totals and unique locations
- **Conversion Bar** — Visual indicator per report entry
- **Persistent Storage** — All data saved to `localStorage`
- **Toast Notifications** — Feedback on every save action
- **Mobile-first** — Optimised for smartphone use

## Project Structure

```
property-dashboard/
├── index.html     # Markup and page structure
├── styles.css     # All styling (CSS variables, components, layout)
├── script.js      # App logic (state, render, localStorage)
├── .gitignore
└── README.md
```

## Deploy to Netlify

### Option A — Drag & Drop
1. Go to [netlify.com](https://netlify.com) and log in
2. Drag the entire `property-dashboard/` folder onto the Netlify dashboard
3. Done — your site is live instantly

### Option B — GitHub + Netlify CI
1. Push this repo to GitHub
2. In Netlify: **Add new site → Import from Git**
3. Select your repo
4. Set **Publish directory** to `/` (root)
5. Click **Deploy site**

> No build command needed — this is a static site.

## Run Locally

Just open `index.html` in your browser. No server required.

```bash
# Or serve with any static server, e.g.:
npx serve .
```

## Tech Stack

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- Vanilla JavaScript (ES6+)
- Google Fonts — DM Sans + Syne
- localStorage for persistence

## License

MIT
