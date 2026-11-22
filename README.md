# Omkar Kale — Portfolio Website

A responsive, bilingual (English/German) personal portfolio built with plain HTML, CSS and JavaScript. It is static and can be hosted directly on GitHub Pages — no build tools, framework or server are required.

## Preview locally

You can open `index.html` directly in a browser, or run a local server from this folder:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish with GitHub Pages

1. Create a GitHub repository. For a user site, name it `omkark911.github.io`; for a project site, any repository name is fine.
2. Upload `index.html`, `styles.css`, `script.js` and `README.md` to the repository root.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.
6. GitHub Pages will publish the site. For a user site, the address will be `https://omkark911.github.io/`.

## Personalise before publishing

- Review the project descriptions, publication titles and dates for accuracy.
- Add links to individual project repositories when you have the exact public URLs.
- Add a PDF CV link once you have a recruiter-ready CV to publish (for example, `assets/Omkar-Kale-CV.pdf`).
- If your German level or current study status changes, update the language panel and profile text in both languages.
- The page currently uses Google Fonts (DM Sans, DM Mono and Manrope). It will fall back to system fonts if Google Fonts are unavailable.

## Language switch

The EN/DE button switches all translated page copy and updates the document language. The selected language is saved in browser local storage when available.

### Add your profile photo

Place `Portfolio_Profile_Picture.png` in the same folder as `index.html` before publishing. The profile card is already configured to display it inside a circular frame. Keep the filename and capitalization exactly as shown.
