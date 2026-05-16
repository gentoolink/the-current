# The Current — AI Trends Blog

Plain HTML/CSS blog deployed on Netlify at **automatemission.com**

## Files

- `index.html` — Homepage with featured article + article grid
- `about.html` — About the publication
- `category.html` — Category filter page (AI, ML, Tools, Analysis)
- `style.css` — Full design system (CSS variables, typography, layout)
- `article-*.html` — Five published articles
- No JavaScript frameworks. No build step.

## Deploy to Netlify

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the `/home/ken/automatemission/` folder onto the window
3. Done. Netlify will assign a URL. Add your custom domain `automatemission.com` in site settings.

## Adding Articles

Copy `article-why-ai-code-review.html` as your template. Fill in:
- `<title>` and meta description
- Category pill link
- Article title, subtitle, byline
- Article body content
- Key takeaways list
- Related articles grid
- Update all nav `active` states

## Writing Style

- Headline makes a claim or asks a question (Bernard Marr style)
- Short punchy paragraphs, no filler
- Drop cap on first paragraph
- Pull quote or blockquote mid-article
- Key takeaways box at end
- No: "revolutionary", "game-changing", "unprecedented"
- No: exclamation points, emojis, generic tech blog filler

## Architecture

- Fonts: Playfair Display (headlines) + Source Serif 4 (body) via Google Fonts
- All icons are inline SVG — no external icon CDNs
- Subtle noise texture overlay on body
- Amber accent (#D97706) on warm off-white (#FAFAF8)
- Reading time, category tags, newsletter signup on all pages
