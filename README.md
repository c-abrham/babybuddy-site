# Baby Go website

Static site for Google Play Console (developer website + privacy policy URL).

## Files

| File | Purpose |
|------|---------|
| `index.html` | Home / about page |
| `privacy.html` | Privacy policy (Play Store requires a public URL) |
| `delete-account.html` | Account deletion instructions (Play Store Data safety) |
| `styles.css` | Shared styling |

## Option A — GitHub Pages (free, gives you a real URL)

1. Push this `website/` folder to a GitHub repository.
2. On GitHub: **Settings → Pages → Build from branch**.
3. Set folder to `/website` on `main` (or move files to `/docs` and use `/docs`).
4. Your URL will be like `https://c-abrham.github.io/babygo-site/` (repo name: `babygo-site`).

Use that URL in Play Console. Privacy policy URL: add `/privacy.html`. Delete account URL: add `/delete-account.html`.

## Option B — Google Sites (free, no GitHub)

1. Go to [sites.google.com](https://sites.google.com) → **Blank** site.
2. Title: **Baby Go**.
3. Copy text from `index.html` into the home page (open the file in a browser to preview).
4. Add a second page **Privacy policy** — copy from `privacy.html`.
5. **Publish** → copy the published URL (e.g. `https://sites.google.com/view/babygo-app`).

Play Console:

- **Website:** home page URL  
- **Privacy policy:** link to privacy page  

## Option C — Preview locally

Open `index.html` in your browser (double-click the file). Links work when all files stay in the same folder.

## Contact email

Pages use **cabraham3221@gmail.com**. Change it in the HTML files if you use a different support address.
