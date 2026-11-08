# PACE — Video Background Website

An original road-running themed landing page built for the HTML5 video background assignment.

## Files
- `index.html` — page structure and HTML5 video element
- `styles.css` — positioning, overlay, responsive layout, and Flexbox styling
- `assets/background-video.mp4` — supplied sample video (about 2.9 MB)

## Preview locally
Open `index.html` in a browser. Keep the `assets` folder beside it so the video path works.

## Publish with GitHub Pages
1. Create a new GitHub repository (for example, `video-background-assignment`).
2. Upload **all** files and folders from this project. `index.html` must be in the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish. Your site URL will look like:
   `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`
7. Submit that published URL to your instructor.

## Assignment concepts demonstrated
- HTML5 `<video autoplay muted loop playsinline>` for the background.
- `position: relative` on the hero as the containing block.
- Absolutely positioned video and shade layers.
- `z-index` / `isolation` to layer the video, overlay, and foreground content.
- Flexbox to center the hero content and arrange the navigation and calls to action.
- Responsive CSS and a reduced-motion preference.

## Before submitting
- Replace `hello@example.com` in the footer with an email address if you want the contact link to work.
- Add your name to the HTML comment if your instructor requires it.
- Test the published page on a phone and desktop.
