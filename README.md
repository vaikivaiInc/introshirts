# Introshirts website

*Quietly searching for kindred spirits.*

A two-page static site — no build step, ready for GitHub Pages.

```
index.html      Home page
story.html      Founder's story (her words)
styles.css      Shared styles for both pages
assets/         Logo, hoodie photos, artwork, favicon
.nojekyll       Tells GitHub Pages to serve the files as-is
```

## Publish on GitHub Pages

1. Create a new repository on GitHub (for example `introshirts`). Keep it **Public**.
2. Upload everything in this folder to the repository root (**Add file → Upload files**, then drag in the files *and* the `assets` folder). `index.html` must sit at the top level, not inside a subfolder.
3. Go to **Settings → Pages**. Under *Build and deployment*, set **Source** to *Deploy from a branch*, choose **main** and **/ (root)**, then **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.
5. Custom domain (optional): enter it under **Settings → Pages → Custom domain** and add the DNS records GitHub shows you.

## Brand notes

- Logo teal: `#0097b2`. Every "Hi" on the site uses it — wrap the word like this: `<span class="hi">Hi</span>`.
- Colours and fonts are set once at the top of `styles.css` (`:root`).

## Before launch

- Email sign-up is a placeholder. Connect a service (Mailchimp, Formspree, etc.) in `index.html`.
- Add prices and a way to order (shop link, order form or contact) — the product cards say "Available now".
- Add social links, a contact email, and privacy / shipping / returns pages.
- Founder to approve the story text and the photos.
