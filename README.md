# Stanza by Whitelion — Landing Page

Distributor landing page for PARÉ, LUFT, Whitelion AirQube and LMT Automation.
Files: `index.html` (page), `data.js` (all product text/data), `images/` (all product images). Keep them together.

## Notes
LUFT product names were read from the catalogue images. Please verify them against the official LUFT price list before publishing.

## Publish with GitHub Pages
1. Create a new repository on github.com (e.g. `stanza-website`).
2. Click **Add file → Upload files**, drag in the whole contents of this folder (`index.html`, `data.js`, `images` folder, `.nojekyll`), then **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to `main` and folder to `/ (root)`, then **Save**.
4. After a minute your site is live at `https://<your-username>.github.io/<repo-name>/`.

## Add your contact details
Open `index.html`, search for `const CONTACT=` and fill in:
`const CONTACT={whatsapp:"919812345678",phone:"+919812345678",email:"sales@yourdomain.com"};`
(WhatsApp number: digits only, with country code.)
