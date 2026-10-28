# Rafael Santos Oliveira — SAP Business One Consultant Website

A static, single-page website built from Rafael's resume content. No build tools or server required.

## Structure

```
index.html              Main page (About, Services, Experience, Achievements, Skills, Contact)
css/style.css            All styling (teal/navy palette matching the resume)
js/main.js                Scroll progress bar, mobile nav, reveal animations, contact form (mailto)
assets/images/profile.jpg  Rafael's headshot, shown in the hero
assets/files/Rafael-Santos-Oliveira-Resume.pdf  Resume used by the "Download Resume" button
```

## Profile photo

`assets/images/profile.jpg` already has Rafael's headshot. To swap it, just replace that file with another portrait (roughly 600x720px works best). If the file is ever missing, the hero automatically falls back to a clean "RSO" monogram.

## Preview locally

Just open `index.html` in a browser, or run a quick local server from this folder:

```bash
npx serve .
```

## Deploy (free options)

- **GitHub Pages**: push this folder to a repo and enable Pages on the `main` branch.
- **Netlify / Vercel**: drag-and-drop this folder into their dashboard, or connect a repo.
- **Custom domain**: once deployed, point a domain (e.g. rafaelsoliveira.com) at it via your registrar's DNS.

## Customize

- Contact details, services, experience and skills all live directly in `index.html` — edit the text in place.
- Colors and fonts are CSS variables at the top of `css/style.css` (`:root`).
- The contact form currently opens the visitor's email client pre-filled (no backend/server needed). To collect submissions directly, swap it for a form service like Formspree or Netlify Forms.
