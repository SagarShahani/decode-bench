# Decode Bench

A CyberChef-style workbench that runs entirely in your browser. Chain operations to encode, decode, hash, encrypt and inspect data. No server, no build step, nothing leaves your device.

## Use it

Open the published GitHub Pages site, or open `index.html` directly in a browser.

## Features

- About 98 operations: Base64/32/58, hex, URL, hashes, HMAC, AES, ciphers, JSON, compression, and more
- Magic: automatically finds likely decodings, up to three layers deep
- Command palette (Ctrl+K), undo and redo, step previews and breakpoints
- Light, dark and auto themes with five accent colours
- Example library, saved recipes, JSON export and import, and share links

## Deploy

1. Put `index.html` in the root of this repository.
2. Go to Settings, then Pages.
3. Choose "Deploy from a branch", pick `main` and `/ (root)`, then save.

## Add your own operation

Everything lives in the `OPS` array inside `index.html`:

```js
{ n: 'My op', c: 'Text', i: 'What it does.', a: [A('Option', 'text', 'default')],
  f: (bytes, [option]) => B(T(bytes).toUpperCase()) }
```
