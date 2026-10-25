# Ailyn Decasa – Student Portfolio

A static site built with plain HTML, CSS, and JavaScript. No install or build step.

## Open locally
Double-click `index.html`. (Skill logos and fonts load from the internet, so connect to Wi-Fi.)

## Replace the placeholders
Open `index.html` and search for `[` — every placeholder is in square brackets. Delete the brackets when you replace the text.
- **Profile photo:** save it as `assets/profile.jpg`, then replace the `<div class="photo">…</div>` line with `<img src="assets/profile.jpg" alt="Photo of Ailyn Decasa">`.
- **Skill levels:** edit the line under each skill (Beginner, Currently Learning, or Intermediate). Be honest.
- **Project screenshots:** save images in `assets/` (e.g. `project1.png`). Replace each `<div class="shot">…</div>` with `<img src="assets/project1.png" alt="Screenshot of PROJECT NAME">`.
- **Project links:** uncomment the `View Project` line in a project card and put in the real URL.
- **GitHub:** change `https://github.com/YOUR-USERNAME` and the `[YOUR GITHUB PROFILE]` text.
- **Colors:** change the variables at the top of `style.css`.

## Publish on GitHub Pages
1. Create a repository on GitHub (e.g. `portfolio`).
2. Upload `index.html`, `style.css`, `script.js`, `README.md`, and the `assets` folder.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
5. After a minute or two, your site appears at `https://YOUR-USERNAME.github.io/portfolio/`.
