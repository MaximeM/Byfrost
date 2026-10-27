# Byfrost website

Static landing pages for Byfrost. No build step: everything is served as is.

- `index.html`: main landing page, served at `/`.
- `b/index.html`: alternate landing page, served at `/b`. It shares `images/`, `fonts/` and `favicon.svg` with the root through `../` paths.

Preview locally:

```bash
npx http-server -p 8080
```

Deployed on Railway, which detects the root `index.html` and serves it as a static site.

## Credits

- Sora and Oxanium fonts: SIL Open Font License (see `fonts/`).
- Blender screenshot: Blender Foundation, CC BY.
- Other photos and screen content are generated images.
