# Michelle Salcedo — Nokia 3310 Linktree

A portfolio/linktree built as an interactive Nokia 3310 phone experience.
Single `index.html` file, no build tools, no frameworks.

## Live files

| File | Purpose |
|------|---------|
| `index.html` | Everything — HTML, CSS, JS in one file |
| `Nokia.png` | Phone image used as the UI shell |

## Features

- Boot sequence + idle clock screen
- 5x5 app menu grid with pixel SVG icons
- Inquiry form (contact)
- Links screen (LinkedIn, Instagram, Website)
- Book a Call shortcut
- Gallery with 6 images (navigate with right d-pad)
- Horoscope, Snake, FM Radio, Calculator, Tamagotchi, and more
- Multiple color themes (mono, green, amber, blue)
- Button overlays mapped to the physical Nokia keys

## Deploy

Works as a static site — just upload `index.html` and `Nokia.png` together.

Compatible with GitHub Pages, Netlify, Vercel, or any static host.

### GitHub Pages (quickest)

1. Push this repo to GitHub
2. Go to **Settings → Pages → Source → main / root**
3. Your site will be live at `https://<username>.github.io/<repo-name>`

## Tech

- Vanilla HTML / CSS / JavaScript
- [VT323](https://fonts.google.com/specimen/VT323) font via Google Fonts
- Web Audio API for button sounds
