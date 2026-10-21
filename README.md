# Website of Veronika Yakubu: static files

Plain HTML, CSS and self-hosted fonts. No build step, no cookies, no external requests.

| File | Page |
|---|---|
| `index.html` | Home (English) |
| `de.html` | Startseite (Deutsch) |
| `impressum.html` / `legal-notice.html` | Impressum (DE / EN) |
| `datenschutz.html` / `privacy-policy.html` | Datenschutzerklärung (DE / EN) |

## Publish on GitHub Pages (free)
1. Create a GitHub account and a new **public** repository. If you name it `<your-username>.github.io`, the site is served at the root address; with any other name it is served at `https://<your-username>.github.io/<repository>/`.
2. "Add file" > "Upload files": drag in the **contents** of this folder (not the folder itself) and commit.
3. Repository "Settings" > "Pages": Source = "Deploy from a branch", branch `main`, folder `/ (root)`, Save.
4. After a minute the site is live. Open every page and click every link once.

## Things to keep in mind
- GitHub's terms say Pages must not be used as a free host for an online business or a site primarily directed at facilitating commercial transactions. A personal site that presents your profile and how to contact you is a different thing; do not add shop, payment or booking features.
- The privacy pages describe GitHub Pages as the host. If you change the host, update both privacy pages.
- Once you have a custom domain, add it under "Settings" > "Pages" and switch on "Enforce HTTPS".
- Review the Impressum and privacy texts again whenever you add features (forms, analytics, embedded videos or maps change what the privacy notice must say).

## Fonts
Inter, Space Grotesk and JetBrains Mono are licensed under the SIL Open Font License (see `fonts/licenses/`).
