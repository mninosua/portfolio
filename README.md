# Maria Niño-Suastegui — Portfolio Starter

A responsive, single-page portfolio built with plain HTML, CSS, and JavaScript. It publishes on GitHub Pages without a build step.

## Files
- `index.html` — page content and project placeholders
- `styles.css` — visual design, palette, responsive layouts
- `script.js` — mobile navigation and current-year labels
- `assets/` — place your résumé PDF and future local assets here

## Preview locally
1. Download and unzip this folder.
2. Open `index.html` in your browser.

## Publish with GitHub Pages
1. Create a GitHub repository, for example `maria-portfolio`.
2. Upload the *contents* of this folder to the repository root. Make sure `index.html` is at the top level.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for deployment. GitHub will show the public site URL in Pages settings.

## Replace the placeholders

### Résumé PDF
Place your real PDF at `assets/maria-resume.pdf`, or update the link in `index.html` to match your filename.

### YouTube videos
For each video, open YouTube → **Share → Embed**. Copy the `src` URL from the iframe and place it in a project case study. Example:

```html
<div class="video-frame">
  <iframe
    src="https://www.youtube-nocookie.com/embed/VIDEO_ID"
    title="Descriptive title for your video"
    loading="lazy"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    referrerpolicy="strict-origin-when-cross-origin"
    allowfullscreen>
  </iframe>
</div>
```

Add this CSS to `styles.css`:

```css
.video-frame { aspect-ratio: 16 / 9; width: 100%; overflow: hidden; background: #27251f; }
.video-frame iframe { display: block; width: 100%; height: 100%; border: 0; }
```

### Images, presentations, and writing
Add image files to `assets/` and use descriptive `alt` text. PDFs can be linked for viewing or downloading; presentations can be linked from a public sharing URL or exported as PDF. For any work that isn't public, do not upload it or link it without permission.

### Contact and profile links
Search `index.html` for `YOUR.EMAIL@example.com` and the placeholder LinkedIn/YouTube URLs. Replace them before publishing.

## Design notes
The palette uses warm cream, brick red, terracotta, olive, forest green, and deep brown. Layouts shift to one column on mobile. Keyboard focus, a skip link, mobile navigation, and reduced-motion preferences are supported. Google Fonts load online with system fallbacks.
