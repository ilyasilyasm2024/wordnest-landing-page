# WordNest landing page

Static site (no build step on the server): `index.html` (English), `fr/`, `ar/` (right-to-left), `style.css`, `assets/`, `media/` (video posters). The videos are on YouTube (ids in `VIDEOS` in the script); the player loads only when the visitor taps play.(video posters).

The explainer videos are on YouTube (ids in `VIDEOS` in the script); the player loads only when the visitor taps play.

- Edit texts and links in [`scripts/build-site.js`](../../scripts/build-site.js), then run `npm run site` to regenerate the three pages. `style.css` is edited by hand.
- **Publish on GitHub Pages:** create a public repo named `wordnest`, upload the *contents* of this folder (not the folder itself), then Settings → Pages → Deploy from branch → `main` / root. The site appears at `https://ilyasilyasm2024.github.io/wordnest/`.
- If the address is different (own domain, other repo name), change `BASE` in the script and regenerate.
- The privacy policy stays where it is (`wordnest-privacy` repo); the app and Play Console link to it.
- The Google Play button carries `referrer=utm_source=website&utm_content=<lang>` so Play Console shows installs that came from the site.
# wordnest-landing-page
