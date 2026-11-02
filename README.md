# PocketDesk Web Apps

A standalone, local-first website containing four browser tools:

PocketDesk's logo uses four simple tiles to represent its collection of small, practical tools. The standalone SVG wordmark and square icon are included as `PocketDesk-logo.svg` and `PocketDesk-icon.svg`.

- **Status Saver** — import status photos/videos you can access, preview them, and download individual or multiple files.
- **Image Compressor** — create a compressed JPEG copy with adjustable quality.
- **Text Studio** — count words, characters and lines; change case; copy text.
- **JSON Formatter** — validate, format, minify, and copy JSON.

## Open the site

Open `index.html` in a modern browser. There is no build step, sign-in, backend, analytics, or external library. The page processes selected files and text in the browser.

## Status media access

The website cannot scan WhatsApp's private status folder or read files without the user's selection. Use **Choose files** to import accessible image/video files. On Android, browser file access varies by browser and system version; the native Android app's folder picker may be able to reach a folder the browser cannot.
