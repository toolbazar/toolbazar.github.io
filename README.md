# Tool Bazar

A responsive, static website offering free browser-based PDF and document utilities.

## Run locally

Open `index.html` in a modern browser, or serve the folder with any static web server. No build step is required.

## Included

- Responsive landing page, searchable/filterable tool catalogue and accessible processing dialog.
- Browser-side PDF merge, page extraction/removal/reordering, rotation, watermark, page numbering, text extraction, PDF-to-JPG export and image-to-PDF.
- DOCX text conversion to PDF and PDF text export to a Word-compatible document.
- Privacy and terms pages, robots.txt and sitemap.xml.

## Important functionality notes

- **Compress PDF** rasterizes pages to JPEG and rebuilds the PDF. It can reduce file size, but it flattens content and can reduce quality; it is not a lossless optimizer.
- **PDF to Word** extracts text into a Word-compatible document; original layout and images are not retained.
- **Word to PDF** supports DOCX text/basic formatting only; complex layouts may change.
- **Protect PDF / Unlock PDF** are shown in the catalogue but password encryption/decryption are not implemented in this build.
- Third-party PDF, document and ZIP libraries are loaded from public CDNs. A network connection is required to load them.

## Deployment

The repository name is `toolbazar.githun.io`, which is not the conventional `toolbazar.github.io` Pages repository name. Configure GitHub Pages to deploy from the `main` branch (or merge the reviewed build branch first) and use the custom domain / Pages URL configured in repository settings. Update canonical, sitemap and robots URLs to the actual published domain before launch.
