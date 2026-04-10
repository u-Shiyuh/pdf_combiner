# PDF Combiner

A simple, standalone PDF combiner that merges multiple PDF files into one.

## Features

- Zero installation required - just open the HTML file in your browser
- Combines 2 or more PDF files into a single PDF
- All processing happens locally in your browser (no uploads, completely private)
- Clean, simple interface
- Works on any computer with a modern web browser

## Usage

1. Double-click `pdf_combiner.html` to open it in your browser
2. Click "Select PDF Files" button
3. Choose multiple PDF files (use Ctrl+Click or Cmd+Click to select multiple)
4. Click "Combine PDFs" button
5. The merged PDF will automatically download as `merged_YYYY-MM-DD_HH-MM-SS.pdf`

## Requirements

- Any modern web browser (Chrome, Firefox, Edge, Safari)
- Internet connection (only for loading the pdf-lib library from CDN)

## Technical Details

- Uses [pdf-lib](https://pdf-lib.js.org/) for PDF manipulation
- All processing happens client-side in the browser
- No server required, no data leaves your computer
- Single self-contained HTML file

## License

Free to use for any purpose.
