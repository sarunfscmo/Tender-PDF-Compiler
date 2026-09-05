# Tender PDF Compiler

**Tender PDF Compiler** is a free Windows utility for organizing authorized e-GP bid-response document downloads into one navigable PDF.

> **Status:** v1.0.0 release preparation  
> **Platform:** Windows 10/11, 64-bit  
> **Distribution:** Freeware. Source code is not publicly distributed.

## What it does

Tender PDF Compiler reads a selected Bid Response PDF, identifies listed document-download links, retrieves the linked files, and creates an organized output with:

- a generated table of contents;
- one cover sheet per listed document;
- bookmarks and navigation links;
- optional inclusion of the original Bid Response PDF;
- a warning when a retrieved PDF appears essentially blank;
- separate saving of non-PDF attachments;
- visible failure pages when a document cannot be retrieved; and
- a permanent CSV batch report.

The tool does **not** log in to e-GP, submit bids, modify portal records, or perform bid evaluation.

## Privacy

Processing is performed on the user's computer. Tender PDF Compiler does not upload the selected bid documents to the developer and does not use a developer analytics server.

Network requests are made only as needed to retrieve the source URLs contained in the selected document (or demo URLs in the included synthetic example).

See [PRIVACY.md](PRIVACY.md).

## Demo material

The [`demo-files`](demo-files/) folder contains **15 completely synthetic documents** designed for a public tutorial. They contain no real bidder, public-office, bank, PAN, tax, address, project or signature information.

One file, `02_Blank_Voucher.pdf`, is intentionally blank so the v1.0 blank-document warning can be demonstrated.

After this repository is uploaded, the final synthetic Bid Response PDF will use the public raw GitHub URLs of these files.

## Download

The public Windows executable will be distributed through **GitHub Releases**, not committed as a normal repository source file.

After the release is published:

`https://github.com/sarunfscmo/Tender-PDF-Compiler/releases/latest`


## Verification

Each release should include a SHA-256 checksum alongside the EXE. Users can compare the checksum before running a downloaded copy.

## Important limitation

This utility assists with document retrieval and organization only. A successful download, warning, or generated compilation does **not** determine the validity, responsiveness, eligibility, authenticity or compliance of any bid document. Users must review the source documents themselves.

## Independence

Tender PDF Compiler is an independent utility and is **not affiliated with, endorsed by, or an official product of PPMO, Nepal e-GP, or the Government of Nepal**.

## License

Tender PDF Compiler is freeware, not open source. See [LICENSE.txt](LICENSE.txt).

Third-party components bundled with the application remain under their own licenses. See [THIRD_PARTY_NOTICES_DRAFT.md](THIRD_PARTY_NOTICES_DRAFT.md).
