# Third-Party Notices - Draft for v1.0.0

Tender PDF Compiler's own source code is proprietary/freeware. The compiled
application also contains third-party software under separate licenses.

The current v1.0 build stack includes or may bundle components such as:

| Component | Intended role | License family to preserve in release |
|---|---|---|
| pypdf | PDF reading/writing/merging/navigation | BSD-style |
| pdfplumber | PDF text/layout extraction | MIT |
| pdfminer.six | Text extraction backend | MIT-style permissive license |
| ReportLab | Generated PDF pages | BSD |
| Pillow | Image handling | HPND-style permissive license |
| requests | HTTP client | Apache-2.0 |
| urllib3 | HTTP transport | MIT |
| certifi | CA certificate bundle | MPL-2.0 |
| charset-normalizer | Character encoding support | MIT |
| idna | Internationalized domain names | BSD-style |
| pypdfium2 / PDFium components | PDF rendering used by pdfplumber stack | Multiple permissive/component licenses |
| PyInstaller | Windows packaging | GPL with PyInstaller bootloader exception |

**Before publishing the final EXE**, generate the notice set from the exact
packages included in the tested release build and include the applicable
license/copyright texts. This draft is a release checklist, not final legal advice.
