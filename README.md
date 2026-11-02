# PocketDesk Web Apps

A standalone, local-first website containing four browser tools. The standalone SVG wordmark and square icon are included as `PocketDesk-logo.svg` and `PocketDesk-icon.svg`.

- **Status Saver** — finds and downloads WhatsApp Status updates from the `.Statuses` folder as one ZIP archive.
- **Image Compressor** — create a compressed JPEG copy with adjustable quality.
- **Text Studio** — count words, characters and lines; change case; copy text.
- **JSON Formatter** — validate, format, minify, and copy JSON.

## Open the site

Open `index.html` in a modern browser. There is no build step, sign-in, backend, analytics, or external library. The page processes data on your device.

## WhatsApp Status access

Choose WhatsApp's `.Statuses` folder, or a parent folder that contains it. The site searches for `.Statuses` and reads only supported media files inside that folder; it ignores other gallery folders and does not access chats, contacts, or WhatsApp's private database. Preview is available, and **Download all statuses (.zip)** packages the discovered statuses into one archive. The browser asks for read access to the selected folder. Some Android/browser combinations do not expose WhatsApp's status cache because Android and WhatsApp restrict access to app data. In that case, try the native Android Status Saver folder picker. No website can request blanket permission to WhatsApp's private data.