# 📄 PDF Editor Pro

A fully browser-based PDF editor built with HTML, CSS, and JavaScript. No installs, no backend, no server — just open the link and start editing.

**Live Demo:** [khushpatel1234.github.io/pdfeditor](https://khushpatel1234.github.io/pdfeditor)

---

## ✨ Features

### ✏️ Text Editing
- Click any existing PDF text to edit it inline
- Change font, size, and color of any text line
- Delete unwanted text lines with a single click

### 🎨 Annotation Tools
- Freehand drawing with adjustable stroke width & opacity
- Highlighter, underline, and strikethrough
- Sticky notes (draggable, editable)
- Add new text boxes anywhere on the page

### 🔷 Shape Tools
- Rectangle, filled rectangle, ellipse
- Line and arrow
- Redact / black-out sensitive content

### 🖼️ Media
- Insert images anywhere on a page

### 📑 Page Management
- Rotate pages clockwise / counter-clockwise
- Delete or duplicate pages
- Thumbnail sidebar for quick navigation
- Merge multiple PDFs into one
- Split PDF by page range or specific pages

### 💧 Other
- Watermark all pages with custom text
- Page background color
- Text search across all pages
- Undo / Redo (50-step history per page)
- Zoom 50%–300% + Fit Width

### 💾 Export
- All edits baked into a downloadable PDF
- Annotations, text edits, shapes, and images all preserved

---

## 🚀 How to Use

1. Open the app in your browser
2. Click **Choose PDF File** or drag & drop a PDF
3. Use the toolbar to select a tool
4. Click **Download PDF** when done

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `W` | Edit existing text mode |
| `V` | Select tool |
| `D` | Freehand draw |
| `T` | Add text box |
| `E` | Eraser |
| `R` | Rectangle |
| `H` | Pan / hand tool |
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |
| `Ctrl + S` | Download PDF |
| `Esc` | Exit current mode |

---

## 🛠️ Built With

- [PDF.js](https://mozilla.github.io/pdf.js/) — PDF rendering in the browser
- [pdf-lib](https://pdf-lib.js.org/) — PDF generation and export
- Vanilla HTML / CSS / JavaScript — no frameworks

---

## 📦 Running Locally

No build step needed. Just open the file:
```bash
# Clone the repo
git clone https://github.com/yourusername/pdf-editor.git

# Open in browser
open pdf_editor.html
```

Or use **Live Server** in VS Code for auto-reload on save.

---

## ⚠️ Limitations

- Editing existing PDF text works best on standard PDFs (Word exports, reports, forms). Complex PDFs with custom embedded fonts may have slight position offsets.
- This is a client-side tool — no data is ever uploaded to any server. Your PDFs stay on your device.

---

## 📄 License

MIT — free to use, modify, and distribute.
