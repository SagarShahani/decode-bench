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
python3 -m http.server 8000
# Then visit http://localhost:8000
```
## Author
Sagar Shahani

GitHub: **@SagarShahani**

LinkedIn: **sagar-ali-66a324277**

Medium: **@SaGarShahani**
