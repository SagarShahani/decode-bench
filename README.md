# Decode Bench

> A CyberChef-style workbench that runs entirely in your browser. Chain operations to encode, decode, hash, encrypt, and inspect data — no server, no build step, nothing ever leaves your device.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://sagarshahani.github.io/decode-bench/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](#license)
[![Made with](https://img.shields.io/badge/made%20with-HTML%20%2F%20JS-orange.svg)](#)

---

## Overview

**Decode Bench** is a single-file, client-side data manipulation tool inspired by GCHQ's CyberChef. It lets you build a pipeline of operations — decode Base64, verify a hash, decrypt AES, parse JSON, and more — and watch the data transform step by step.

Everything executes locally in your browser. No data is transmitted, logged, or stored on any server.

**Live site:** https://sagarshahani.github.io/decode-bench/

---

## Features

- **~98 operations** across encoding, hashing, encryption, compression, parsing, and text analysis
- **Magic mode** — automatically detects and decodes likely obfuscated input up to three layers deep
- **Command palette** — press `Ctrl+K` (`⌘K` on macOS) to search and insert operations instantly
- **Step previews and breakpoints** — inspect intermediate output at any stage of the pipeline
- **Undo / redo** — full history of pipeline edits
- **Themes** — light, dark, and auto, with five accent colours
- **Recipe management** — save, load, export, and import recipes as JSON; generate shareable links
- **Zero dependencies** — one `index.html` file, works offline

---

## Operation Categories

| Category | Examples |
|---|---|
| Encoding | Base64, Base32, Base58, Hex, URL, HTML entities |
| Hashing | MD5, SHA-1, SHA-256, SHA-512, HMAC |
| Encryption | AES, XOR, ROT13, ROT47, Vigenère |
| Compression | Gzip, Deflate, Zlib |
| Parsing | JSON, JWT, URL, timestamps |
| Text | Case conversion, whitespace normalisation, character frequency |

---

## Usage

### Run it online
Open **https://sagarshahani.github.io/decode-bench/** in any modern browser.

### Run it locally
```bash
git clone https://github.com/SagarShahani/decode-bench.git
cd decode-bench
# Open index.html directly, or serve it:
python3 -m http.server 8000
# Then visit http://localhost:8000

Author
Sagar Shahani

GitHub: @SagarShahani

LinkedIn: sagar-ali-66a324277

Medium: @SaGarShahani


---

## How to paste this in

1. Open your repo → click **README.md**.
2. Click the **pencil icon** (✏️ Edit this file) at the top right of the file view.
3. Select all (`Ctrl+A`) and delete the old contents.
4. Paste the block above.
5. Scroll down → **Commit changes** → confirm.

GitHub Pages will redeploy automatically in ~1 minute — but note the README is only what shows on the repo page; your actual site is driven by `index.html`, which is already correct.

---

### A few small things worth doing after:

1. **Add a LICENSE file** — the README references MIT. On the repo Code tab: **Add file → Create new file** → name it `LICENSE` → GitHub offers a template picker → choose **MIT License**.
2. **Fill in the About panel** — click the ⚙️ gear next to *About* on the right of the repo page:
   - **Description:** `CyberChef-style in-browser encoder/decoder. 98 ops, Magic, recipes — all client-side.`
   - **Website:** `https://sagarshahani.github.io/decode-bench/`
   - **Topics:** `cybersecurity`, `cyberchef`, `encoding`, `decoding`, `tools`, `javascript`, `client-side`
3. **Fix your password** — Settings → Password and authentication.
