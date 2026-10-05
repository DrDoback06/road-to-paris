# Road to Paris 42.2

The existing Road to Paris progressive web app, published from the supplied
`Road_to_Paris_42_2_PWA.zip`.

**Open and install:** https://drdoback06.github.io/road-to-paris/

## Install on a phone

- **Android:** open the link in Chrome, tap the three-dot menu, then
  **Install and create shortcut → Install**. Some versions label this
  **Install app** or **Add to Home screen**.
- **iPhone:** open the link in Safari, tap **Share → Add to Home Screen**,
  turn on **Open as Web App** if shown, and tap **Add**.

Allow the app to finish its first online load before using it offline.
Progress, workout notes, supplement ticks and shopping extras stay on each
device; they do not sync between phones or with the ChatGPT shopping task.

## Contents and hosting

The app contains 182 training days, a four-week dinner rotation with 28 recipes,
supplement routines, and weekly shopping lists. The supplied application and
data files are preserved.

GitHub Pages serves the root of the `main` branch. `.nojekyll` publishes the
static files directly. No build step or server is required.

When updating a cached app file, also change the cache version in `sw.js` so
installed copies can pick up the new release after their open app windows close.

The standalone preview and the original `INSTALL.txt` are included from the ZIP.
