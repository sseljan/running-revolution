# The Running Revolution Website

This folder contains a static website version of a History Day trifold project.

## Local Preview

Run a simple local web server from this folder:

```bash
python3 -m http.server 8080
```

Then open:

`http://localhost:8080`

## File Layout

- `index.html` - page content and section structure
- `styles.css` - styling and responsive layout
- `Untitled 12.jpg` - hero image with the full trifold
- `assets/images/` - extracted high-quality source images from the DOCX package

## Deploy Options

### Netlify (fastest)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag this entire folder into the upload area.
3. Netlify gives you a shareable URL immediately.

### Vercel
1. Create a new project in [https://vercel.com/](https://vercel.com/).
2. Import/upload this folder as a static site.
3. Deploy and share the generated URL.

### GitHub Pages
1. Put these files in a GitHub repository.
2. In repository settings, enable GitHub Pages from the default branch root.
3. Share the published Pages URL.

## Privacy Note

The hero image includes your son. If needed, use a private or unlisted sharing option.
