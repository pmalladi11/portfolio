# Pranav Malladi — Engineering Portfolio

Plain HTML/CSS site for GitHub Pages. No build step, no frameworks.

## Folder layout

```
index.html                  Home: intro, project list, About (personal details), Contact
tsa-robot.html              TSA Robotics robot blog
electric-vehicle.html       Science Olympiad EV blog
fpv-drone.html              TSA Drone Challenge blog
style.css                   All styling (colors, fonts, widths at the top)
assets/                     All photos, diagrams, and screenshots (prefixed by project:
                            tsa-*, ev-*, drone-*), plus docs/resume.pdf
```
## Publish on GitHub Pages

1. Create a public repository named exactly `<your-username>.github.io`.
2. Upload everything in this folder to the repository root (index.html must be at the top level).
3. In the repo, go to **Settings → Pages**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. After a minute the site is live at `https://<your-username>.github.io`.

## Editing checklist

- **Yellow highlighted text** (`<span class="todo">`) marks things to fill in. Replace the text and delete the span.
- **Images:** drop a file into `assets/`, then replace the dashed placeholder `<div class="placeholder">…</div>` with
  `<img src="assets/your-photo.jpg" alt="Short description">`. An HTML comment above each placeholder shows the exact line.
- **Videos:** upload to YouTube (unlisted is fine) and use the `<iframe>` snippet in the comment above each video placeholder. GitHub rejects files over 100 MB, so avoid committing large videos.
- **Images should be resized** to ~1600 px wide and compressed (JPG) so pages load fast.
- **Resume:** export a PDF to `assets/docs/resume.pdf`. Remove your phone number and home address before publishing; the site is public.
- **Google Docs:** set each linked doc's sharing to "Anyone with the link → Viewer" so reviewers can open them.
