# Tool Bazar

A responsive, static website offering free browser-based PDF and document utilities.

## Live website

https://toolbazar.github.io/

## Run locally

Open `index.html` in a modern browser, or serve the folder with any static web server. No build step is required.

## Included

- Responsive landing page, searchable/filterable tool catalogue and accessible processing dialog.
- Browser-side PDF merge, page extraction/removal/reordering, rotation, watermark, page numbering, text extraction, PDF-to-JPG export and image-to-PDF.
- DOCX text conversion to PDF and PDF text export to an editable DOCX.
- Privacy and terms pages, custom 404 page, robots.txt and sitemap.xml.

## Important functionality notes

- **Compress PDF** rasterizes pages to JPEG and rebuilds the PDF. It can reduce file size, but flattens content and may reduce quality; it is not a lossless optimizer.
- **PDF to Word** extracts text into an editable DOCX; original layout and images are not retained.
- **Word to PDF** supports DOCX text/basic formatting only; complex layouts may change.
- **Protect PDF / Unlock PDF** are listed but password encryption/decryption are not implemented in this build. The interface reports this limitation instead of claiming success.
- Third-party PDF, document and ZIP libraries are loaded from public CDNs. A network connection is required to load them.

## Deployment

This repository is named `toolbazar.github.io`, so GitHub Pages is expected to publish the site at https://toolbazar.github.io/. GitHub Pages must be enabled for the `main` branch (root folder). The sitemap and canonical URLs are configured for that root domain.
