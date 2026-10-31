# Veloce Digital Canada — GitHub Pages website

## Included
- `index.html` — landing page for both games
- `witch-garden/support.html` and `witch-garden/privacy.html`
- `astral-boom/support.html` and `astral-boom/privacy.html`
- `assets/style.css` — shared responsive styling

## Before publishing / App Store review
1. Replace **every** `SUPPORT_EMAIL_HERE` with a monitored support email.
2. Review and replace every `[VERIFY ...]` section in both privacy policies. These are intentionally unfinished to avoid false privacy claims. Confirm what the actual shipping builds and third-party SDKs do.
3. Astral Boom's policy includes Game Center. Witch Garden mentions Game Center only as a possible future feature; revise when it is actually enabled.
4. Check that all described features match the shipping version of each game.
5. Test all links on a phone and desktop. Make sure support and privacy pages are public and accessible without login.
6. Complete App Store Connect App Privacy disclosures separately; a policy page does not replace the questionnaire.

## Deploy (free GitHub Pages)
1. Create a **public** GitHub repository named `veloce-digital`.
2. Upload the **contents of this folder** to the repository root (not the ZIP as a single file). You should see `index.html` at the top level.
3. In repository **Settings > Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**, then save.
4. Wait for the deployment to finish. Visit `https://YOURUSERNAME.github.io/veloce-digital/`.
5. Use these URLs in App Store Connect, substituting your actual username:
   - Witch Garden support: `https://YOURUSERNAME.github.io/veloce-digital/witch-garden/support.html`
   - Witch Garden privacy: `https://YOURUSERNAME.github.io/veloce-digital/witch-garden/privacy.html`
   - Astral Boom support: `https://YOURUSERNAME.github.io/veloce-digital/astral-boom/support.html`
   - Astral Boom privacy: `https://YOURUSERNAME.github.io/veloce-digital/astral-boom/privacy.html`

No build tools, paid hosting, or GitHub Actions workflow is required for this static website.
