# Your Name — Personal Site

A minimal, multi-page personal site (Home / About / Projects / Blog) built with plain HTML & CSS — no build step, no dependencies.

## Files
- `index.html` — homepage
- `about.html` — about page
- `projects.html` — projects list
- `blog.html` — blog index
- `post-1.html` — example blog post (copy this to add new posts)
- `style.css` — all styling

## How to put this on GitHub Pages

1. Create a new repo on GitHub named exactly `yourusername.github.io` (swap in your real username).
2. Upload all these files to the repo (drag-and-drop on github.com works fine, or use git).
3. Go to **Settings → Pages** in the repo, set Source to "Deploy from a branch," branch `main`, folder `/ (root)`.
4. Wait a minute or two — your site will be live at `https://yourusername.github.io`.

## Customizing
- Replace "Your Name" everywhere (search & replace across all files).
- Update the email and GitHub/LinkedIn links in the `<footer>` of each page and the About page.
- Edit the bio, project cards, and blog posts with your real content.
- To add a blog post: duplicate `post-1.html`, rename it, edit the title/date/body, and add a link to it in `blog.html`.
- Colors and fonts live at the top of `style.css` under `:root` — change `--accent` to shift the whole site's accent color.

## Notes
- Fonts (Fraunces, Source Serif 4, Inter) load from Google Fonts via a CDN link in each page's `<head>`.
- The layout is responsive and works down to mobile widths.
