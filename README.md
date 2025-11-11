# Drag and Drop Viewer

A simple, self-contained HTML file for viewing Markdown, text, and CSV files in your browser.

- **Run locally:** Download `index.html` to your desktop and double-click to open in your browser.
- **Live version:** https://drag-and-drop-viewer.netlify.app
- **GitHub:** https://github.com/choonkeat/drag-and-drop-viewer

## Features

- **Drag and drop** - Drop one or multiple `.md`, `.txt`, or `.csv` files anywhere on the page
- **Click to upload** - Click the dropzone or "+ Add" button to select files
- **Multiple formats** - Supports Markdown, plain text, and CSV files
- **CSV tables** - CSV files are automatically rendered as formatted tables
- **Browser history** - Navigate between files using browser back/forward buttons
- **File list sidebar** - Click any file in the left sidebar to view it
- **Responsive design** - Works on desktop and mobile devices
- **GitHub-flavored styling** - Clean, readable markdown rendering
- **Privacy-focused** - No data leaves your browser

## Usage

1. Open `index.html` in your browser
2. Drag and drop any `.md`, `.txt`, or `.csv` file(s) onto the page, or click to select files
3. View rendered content with proper formatting
4. Use browser back/forward or click files in the sidebar to navigate
5. On mobile, tap the ☰ button to access the file list and "+ Add" button

## Technical Details

- Single HTML file with no build process required
- Uses [marked.js](https://marked.js.org/) from CDN for markdown parsing
- Uses [PapaParse](https://www.papaparse.com/) from CDN for CSV parsing
- All file processing happens client-side
- No server or backend needed
