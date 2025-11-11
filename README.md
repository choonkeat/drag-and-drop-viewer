# Drag and Drop Markdown Viewer

A simple, self-contained HTML file for viewing Markdown files in your browser.

- **Run locally:** Download `index.html` to your desktop and double-click to open in your browser.
- **Live version:** https://drag-and-drop-md-viewer.netlify.app

## Features

- **Drag and drop** - Drop one or multiple `.md` files anywhere on the page
- **Browser history** - Navigate between files using browser back/forward buttons
- **File list sidebar** - Click any file in the left sidebar to view it
- **GitHub-flavored styling** - Clean, readable markdown rendering
- **Privacy-focused** - No data leaves your browser

## Usage

1. Open `index.html` in your browser
2. Drag and drop any `.md` file(s) onto the page
3. View rendered markdown with syntax highlighting
4. Use browser back/forward or click files in the sidebar to navigate

## Technical Details

- Single HTML file with no build process required
- Uses [marked.js](https://marked.js.org/) from CDN for markdown parsing
- All file processing happens client-side
- No server or backend needed
