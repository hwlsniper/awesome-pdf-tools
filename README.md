# Awesome PDF Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of free online PDF tools — with a focus on privacy, no-registration, and client-side processing.

Web-based PDF tools fall into two categories: those that **upload your files to a server** for processing, and those that process **entirely in your browser** using WebAssembly. This list highlights both, with clear labeling so you know what happens to your data.

## Contents

- [Client-Side (No Upload)](#client-side-no-upload)
- [Server-Side (Upload Required)](#server-side-upload-required)
- [Self-Hosted / Open Source](#self-hosted--open-source)
- [Desktop PDF Software](#desktop-pdf-software)
- [Developer Libraries](#developer-libraries)

## Client-Side (No Upload)

*Tools that process PDFs entirely in your browser. Files never leave your device.*

- [PDF Toolbox](https://pdftoolbox.tech) — Free browser-based PDF tools: compress, merge, split, convert, protect, and unlock PDFs. All processing happens client-side using WebAssembly and pdf-lib.js. No uploads, no registration, no limits.
- [SimplePDF](https://simplepdf.eu) — Online PDF editor that works in the browser. Fill forms, add text, sign documents. EU-hosted but files are processed client-side.
- [PDFEscape](https://www.pdfescape.com) — Online PDF editor with form filling and annotation. Basic editing is client-side; some features require upload.
- [Mini-Tools.uk PDF to Image](https://mini-tools.uk/pdf2img) - Self-recommending a client-side PDF to PNG converter. It renders PDF pages in the browser and exports individual PNG pages or a ZIP, which is useful for no-upload PDF page previews and support-ticket screenshots.

## Server-Side (Upload Required)

*Popular tools that upload your files to their servers. Convenient but be mindful of privacy.*

- [SmallPDF](https://smallpdf.com) — Full-featured PDF suite: compress, merge, split, convert, edit, e-sign. Free tier limited to 2 tasks/day. Files uploaded to their servers.
- [iLovePDF](https://www.ilovepdf.com) — Comprehensive PDF tools with API access. Files retained up to 2 hours. Paid plans available.
- [Sejda](https://www.sejda.com) — PDF editor with desktop app option. Free tier: 3 tasks/hour, 200 pages or 50 MB limit.
- [PDF2Go](https://www.pdf2go.com) — Online PDF converter and editor. Files deleted after 24 hours (claimed).
- [PDF Candy](https://pdfcandy.com) — 47 online PDF tools. Desktop version also available. Free tier has file size limits.

## Self-Hosted / Open Source

*Run your own PDF processing server or integrate PDF manipulation into your app.*

- [Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF) — Self-hosted web PDF manipulation tool with 50+ operations. Docker deployment. ⭐ 60K+
- [pdf-lib](https://github.com/Hopding/pdf-lib) — JavaScript library for creating and modifying PDFs in any JS environment. Used by PDF Toolbox for client-side processing. ⭐ 7K+
- [PDF.js](https://github.com/mozilla/pdf.js) — Mozilla's PDF rendering library. Powers Firefox's built-in PDF viewer. ⭐ 50K+
- [pdfmake](https://github.com/bpampuch/pdfmake) — JavaScript library for PDF generation from JSON/HTML. ⭐ 11K+
- [gotenberg](https://github.com/gotenberg/gotenberg) — Docker-powered stateless API for PDF generation from various formats. ⭐ 8K+

## Desktop PDF Software

*Full-featured desktop applications for offline PDF work.*

- [PDF Arranger](https://github.com/pdfarranger/pdfarranger) — Open-source desktop app for merging, splitting, rotating, and rearranging PDF pages. Python/GTK. ⭐ 3K+
- [PDFsam](https://pdfsam.org) — Split and merge PDFs on desktop. Free basic version, paid enhanced version.
- [Okular](https://okular.kde.org) — KDE's universal document viewer with PDF annotation support.

## Developer Libraries

*Programmatic PDF manipulation for developers.*

- [pypdf](https://github.com/py-pdf/pypdf) — Pure Python PDF library for reading, writing, splitting, merging. ⭐ 9K+
- [qpdf](https://github.com/qpdf/qpdf) — C++ library and CLI for PDF transformation. ⭐ 3.5K+
- [PDFKit](https://github.com/foliojs/pdfkit) — JavaScript PDF generation library for Node.js and browser. ⭐ 10K+
- [iText](https://github.com/itext/itext-java) — Java PDF library (AGPL / commercial license).

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

### Criteria for Inclusion

- Tool must be actively maintained
- Clear labeling of server-side vs client-side processing
- Free tier available (freemium OK, trial-only is not)
- No malware, adware, or deceptive practices

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
