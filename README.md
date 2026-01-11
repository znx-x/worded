# Worded

**Worded** is a lightweight, offline-capable Markdown editor that bridges the gap between the simplicity of Markdown and the familiarity of a WYSIWYG interface (like Google Docs).

Designed to be run as a single-page application, it requires no backend server, making it perfect for secure, local document editing.

## Features

* **Visual Editing:** A familiar ribbon-style interface powered by Quill.js.
* **Markdown Core:** Opens and saves `.md` files seamlessly. The editor converts your visual layout to clean Markdown syntax automatically.
* **A4 Page Simulation:** Visualises your document on an A4 canvas for accurate drafting.
* **Print:** Uses the browser's engine for high-quality, selectable text PDFs and printing.
* **Export PDF:** Captures the document exactly as rendered (visual layout preserved).
* **Offline Ready:** Designed to run entirely locally without an internet connection.

## Installation & Setup

Because this version is configured for offline use, you must ensure the dependency files are present in the same directory as `index.html`.

1. **Download the Source:**
    Clone this repository or download the project folder.

2. **Verify Dependencies:**
    Ensure the following files exist in your root folder (alongside `index.html`):
    * `tailwind.js` (Tailwind CSS script)
    * `quill.min.js` (Quill Core)
    * `quill.snow.css` (Quill Theme)
    * `marked.min.js` (Markdown parser)
    * `turndown.js` (HTML to Markdown converter)
    * `html2pdf.bundle.min.js` (PDF Generator)
    * `fonts.css` (Local font definitions)

3. **Run the App:**
    Simply double-click `index.html` to open it in your web browser (Chrome, Edge, Firefox, or Safari).

## Usage

* **Writing:** Type as you would in any word processor. Use the toolbar for formatting (Bold, Headers, Lists).
* **Saving:** Click **Save** to download a `.md` file to your computer.
* **Opening:** Click **Open** to load an existing Markdown file.
* **Exporting:** * Use **Print** (Destination: Save as PDF) for the best quality text.
* Use **Export PDF** for a visual snapshot.

## Running Offline

Rename the `all.min.css.backup` file to `all.min.css` and edit the the import inside `index.html` to refer back to the local file instead of Cloudflare's CDN (`https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css` to `all.min.css`).

## Dependencies

Worded relies on the following open-source libraries:

* [Quill](https://quilljs.com/) - Rich Text Editor
* [Tailwind CSS](https://tailwindcss.com/) - Styling
* [Turndown](https://github.com/mixmark-io/turndown) - HTML to Markdown conversion
* [Marked](https://github.com/markedjs/marked) - Markdown to HTML conversion
* [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) - Client-side PDF generation
* [FontAwesome](https://fontawesome.com/) - Icons

## Licence

Distributed under the MIT Licence. See `LICENCE.md` for more information.
