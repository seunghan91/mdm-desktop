# MDM Converter — Privacy Policy

**Last updated:** 2026-04-16

## Summary

**MDM Converter does not collect, store, transmit, or share any user data.**

All file conversion happens entirely within your browser using WebAssembly. No files are sent to any server.

## Data Collection

We collect **nothing**:

- No personal information
- No file contents
- No usage analytics
- No error reports
- No cookies
- No network requests (the extension does not make any)

## Permissions

This Chrome extension requests **zero permissions** (`"permissions": []` in `manifest.json`). It does not have access to:

- Your browsing history
- Tab contents
- Other extensions
- Your network
- Files outside the extension popup (you must explicitly drop or pick files into it)

## How it works

1. You open the extension popup.
2. You drop or pick a file (HWP / HWPX / PDF / DOCX).
3. The file is read into **your browser's memory only**.
4. A Rust-compiled WebAssembly module bundled inside the extension converts it to Markdown, entirely on your device.
5. The result appears in the popup. You can copy it to your clipboard or save it as a `.md` file.
6. When you close the popup, the in-memory data is discarded.

No step involves a network call, a remote server, or any third party.

## Remote code

The extension contains **no remote code execution**. All JavaScript and WebAssembly are shipped inside the extension package. There are no external `<script>` tags, no dynamic `import()` from URLs, and no `eval()` of remote strings.

## Open source

The source code is fully open and auditable:

- Chrome extension: included in this public release
- Core engine (Rust + WebAssembly): <https://www.npmjs.com/package/@markdown-media/wasm>
- Python binding: <https://pypi.org/project/mdm-parser/>

## Changes to this policy

If we ever change how MDM Converter handles data, this document will be updated and the extension's version will be bumped. You can review the commit history of this file at any time.

## Contact

Questions, concerns, or issues:

- GitHub Issues: <https://github.com/seunghan91/mdm-desktop/issues>
- Developer: Seunghan Kim (seunghan91)

---

MDM Converter is a free and open-source project by **Seunghan Kim (김승한)**.
