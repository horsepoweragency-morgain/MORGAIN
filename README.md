# The Breed That Chooses You — Morgan Horse one-pager

A single-page site promoting the Morgan Horse breed: hero, breed statement, "Feisty By Nature" traits, a community/social section, quotes, and a join/signup band.

## Files
```
index.html          the entire site (structure + styles + scripts in one file)
assets/
  logo-mark.jpg      crest used in the nav, hero, and footer
  logo-full.jpg      full lockup logo (not currently used on this page, kept for reuse)
  banner.jpg         rider photo used as the faded hero backdrop
```

## Before you publish
This page ships with placeholder content you'll want to swap out:
- **Signup form** — the "Join Free" form in the `#join` section only changes the button text on submit; it doesn't send anywhere yet. Point its `<form>` at a real email service (Mailchimp, ConvertKit, Formspree, etc.) or wire up your own backend.
- **Social links** — the Instagram/Facebook/YouTube icons in the join section and quotes/testimonials are placeholders. Replace the `href="#"` links and swap in real quotes from your own community if you'd like.
- **Nav links** — `#breed`, `#feisty`, `#community`, `#join` all scroll to sections on this same page, so no edits needed there.

## Hosting on GitHub Pages
1. Create a new GitHub repository and push these files to it (keep `assets/` alongside `index.html`).
2. In the repo, go to **Settings → Pages**.
3. Under "Build and deployment," set Source to **Deploy from a branch**, pick the `main` branch and `/ (root)` folder, then Save.
4. GitHub publishes the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

For a custom domain, add it in the same Pages settings panel and point your DNS at GitHub's servers per their instructions.
