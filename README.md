# Lebo Makhetha — Portfolio Website

## File Structure

```
lebo_portfolio/
├── index.html    ← Main HTML (structure & content)
├── style.css     ← All styling (colours, layout, animations)
├── main.js       ← JavaScript (scroll animations, nav highlight)
└── README.md     ← This file
```

## How to Run Locally

Just open `index.html` in any browser. No build tools or installs needed.

## How to Deploy

### GitHub Pages (recommended)
1. Create a new GitHub repo named `lebomakhetha.github.io`
2. Upload all three files (`index.html`, `style.css`, `main.js`)
3. Go to Settings → Pages → set source to `main` branch
4. Your site will be live at `https://lebomakhetha.github.io`

### Netlify
1. Go to netlify.com → Add new site → Deploy manually
2. Drag and drop the entire `lebo_portfolio/` folder
3. Done — live in 30 seconds

### Custom Domain
Point your domain's DNS A record to your host's IP,
then add your domain in the host's settings panel.

## What to Update Before Publishing

| File        | What to change                                      |
|-------------|-----------------------------------------------------|
| index.html  | `lebo@example.com` → your real email                |
| index.html  | LinkedIn URL → your actual profile URL              |
| index.html  | GitHub URL → your actual GitHub username            |
| index.html  | Project `href="#"` links → real GitHub repo URLs    |
| index.html  | Stats (years, ticket count) → your real numbers     |
| index.html  | University name → your actual university            |
| index.html  | Previous company name → your actual employer        |

## Customisation

- **Colours** — edit the `:root` variables at the top of `style.css`
- **Fonts** — change the Google Fonts link in `index.html` and update font references in `style.css`
- **Add a project** — copy one of the `.project-card` blocks in `index.html` and update the content
- **Add a cert** — copy one of the `.cert-card` blocks and update the details
