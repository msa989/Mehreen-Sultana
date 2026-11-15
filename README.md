# Mehreen Sultana — Personal Portfolio

A custom-designed, responsive portfolio for a Mathematics undergraduate interested in data analytics, AI, automation, and software development.

**Headline:** Data Analyst | Mathematics Student  
**Location:** Multan, Pakistan  
**Education:** BS Mathematics, Bahauddin Zakariya University — 3rd Semester

## Design and features

- Restrained sage, warm-white, and deep-green visual identity.
- Responsive desktop, tablet, and mobile layouts.
- Semantic HTML, accessible navigation, keyboard Escape handling, and reduced-motion support.
- Lightweight vanilla HTML, CSS, and JavaScript. No build step, API key, or paid service required.
- SEO description, Open Graph metadata, theme color, and SVG favicon.
- Featured ContractGuardian project with its live application link, technical overview, and informational-use disclaimer.
- Contact links for email, GitHub, and LinkedIn.

## Project structure

```
.
├── index.html
├── styles.css
├── script.js
├── favicon.svg
├── vercel.json
└── README.md
```

## Run locally

No package installation is required.

```bash
git clone https://github.com/msa989/Mehreen-Sultana.git
cd Mehreen-Sultana
python -m http.server 8000
```

Open `http://localhost:8000` in your browser. You can also open `index.html` directly, but a local server better reflects deployment behavior.

## Deploy to Vercel

1. Push the repository to GitHub.
2. Sign in to [Vercel](https://vercel.com/) and select **Add New → Project**.
3. Import `msa989/Mehreen-Sultana`.
4. Select **Other** as the framework preset. No build command is needed; use `.` as the output directory if prompted.
5. Deploy. Vercel will provide a production URL and can automatically redeploy when the connected branch changes.

The included `vercel.json` adds basic browser security headers.

## Git initialization and push

For a local project folder that is not already a Git clone:

```bash
git init
git add .
git commit -m "Build personal portfolio"
git branch -M main
git remote add origin https://github.com/msa989/Mehreen-Sultana.git
git push -u origin main
```

For an existing clone:

```bash
git add .
git commit -m "Update portfolio"
git push
```

Do not run `git init` again inside an existing clone.

## Updating the portfolio

- Edit biography, education, roles, contact details, and project descriptions in `index.html`.
- Add future work by extending the project-card pattern.
- Add a CV link only when a final public CV file is available.
- Never commit API keys, passwords, or other secrets to this static site repository.

## Final testing checklist

- [ ] Check desktop, tablet, and mobile widths.
- [ ] Test mobile navigation, link selection, and Escape-key behavior.
- [ ] Check all section anchors and external destinations.
- [ ] Confirm the email link opens the configured mail client.
- [ ] Confirm ContractGuardian opens in a new tab.
- [ ] Check keyboard focus, text contrast, and reduced-motion behavior.
- [ ] Verify page title, description, favicon, and social preview metadata.
- [ ] Check browser console and network panel for missing assets or errors.
- [ ] Verify the deployed Vercel URL and HTTPS.

## Notes

This is a static portfolio: it does not collect visitor data and requires no runtime secrets. ContractGuardian is presented as an informational contract-review aid, not legal counsel.
