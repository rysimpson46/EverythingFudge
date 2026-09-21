# Everything Fudge

Website for Everything Fudge — a handmade small-batch fudge business.

## Structure

```
/
├── index.html          # Main single-page app (all 5 pages)
├── css/
│   └── style.css       # Extracted styles (future)
├── js/
│   └── main.js         # Extracted scripts (future)
├── images/             # Product photos go here
└── pages/              # Future: separate HTML per page if needed
```

## Pages

- **Home** — Hero, flavor ticker, product rows, craft statement
- **Shop** — Order form with flavor picker, size/qty, delivery options, live order summary
- **Gallery** — Asymmetric photo grid
- **About** — Founder story + pull quote
- **Contact** — Inquiry form + contact info

## Roadmap

- [ ] Add real product photography to `/images/`
- [ ] Wire up Stripe for payment processing
- [ ] Connect order form to email (Formspree or similar)
- [ ] Add domain + hosting (Netlify recommended — free, drag & drop)
- [ ] SEO: meta tags, Open Graph image, sitemap

## To deploy on Netlify (free)

1. Go to [netlify.com](https://netlify.com)
2. Drag the entire project folder into the deploy zone
3. Done — you get a live URL instantly

## Tech

Plain HTML/CSS/JS — no frameworks, no build step required.
