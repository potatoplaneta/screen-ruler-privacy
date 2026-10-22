# Screen Ruler privacy and support

Public privacy policy and support pages for the Screen Ruler macOS app by PotatoPlanetStudios.

- Privacy policy: https://potatoplaneta.github.io/screen-ruler-privacy/
- Support: https://potatoplaneta.github.io/screen-ruler-privacy/support.html
- Private support and privacy requests: potatoplanet.studios@gmail.com
- Public bug reports: https://github.com/potatoplaneta/screen-ruler-privacy/issues

## Publishing

GitHub Pages serves the root of `main`. No build step, dependencies, JavaScript, external fonts, or analytics are required. `.nojekyll` enables static hosting. Push changes to `main` to publish.

`styles.css` is unchanged from the Audio Router and Wheel Launcher privacy sites. The PNG artwork is exported from Screen Ruler's selected app icon (the supplied pastel glass tile with a horizontal ruler, circular marker and **16 px** lettering, selected 22 October 2026): `app-icon.png` (256 px), `app-icon-512.png` (512 px), and 16/32 px favicons. Both pages use local assets only. The artwork matches the production macOS icon and preserves the supplied image's transparency. Versioned image URLs refresh browser caches after publication.

For local preview, run `python3 -m http.server 8789 --bind 127.0.0.1` and open http://127.0.0.1:8789/.

## App integration

The app's `AppLinks.swift` owns both URLs. They appear in the Help menu, quick reference, and Settings → Privacy. Use the same URLs in App Store Connect's Privacy Policy URL and Support URL fields. Publishing this repository does not edit App Store Connect metadata.

Content was checked against the app's implementation on October 19, 2026. Recheck screen capture, exports, local storage, permissions, and support practices when app behavior changes. The current app has no in-app purchases, trial, account, or developer-operated backend; do not copy purchase claims from the other apps. Keep private application source, session data, screenshots, signing assets, and build products out of this repository.

GitHub Issues are public and require a GitHub account. Direct private support and privacy requests to the email address above. Do not ask users to upload unredacted screenshots, session files, private notes, or file paths to a public issue.
