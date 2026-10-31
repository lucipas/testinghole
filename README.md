# Simple HTML Site

A minimal, dependency-free static website.

## Structure

```
.
├── index.html          # Main page
├── assets/
│   ├── styles.css      # Styles (responsive, dark mode aware)
│   ├── main.js         # Small progressive-enhancement script
│   └── favicon.svg     # Site icon
└── README.md
```

## Usage

Open `index.html` directly in a browser, or serve the folder locally:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploying

Because it is a plain static site, you can host it anywhere: GitHub Pages,
Netlify, Vercel, Cloudflare Pages, or any static file server. No build step is
required.

For GitHub Pages, enable it in **Settings → Pages** and choose the branch
root as the source.

## Customizing

- **Content:** edit `index.html`.
- **Look and feel:** edit the CSS variables at the top of `assets/styles.css`.
- **Additional pages:** copy `index.html`, rename it, and link to it from the
  navigation.
