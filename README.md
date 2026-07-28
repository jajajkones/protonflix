# DevTools Hub

> 40+ free, fast, and privacy-first browser tools for developers. No sign-up, no tracking. Everything runs locally in your browser.

**Live:** [jajajkones.github.io/protonflix/tools/](https://jajajkones.github.io/protonflix/tools/)
**Root:** [jajajkones.github.io/protonflix/](https://jajajkones.github.io/protonflix/)

---

## What's Inside

A comprehensive collection of standalone HTML tools organized by category. Each tool is a single self-contained file — no build step, no dependencies, no server required.

### Text & String Tools
| Tool | Description |
|------|-------------|
| [JSON Formatter](tools/json-formatter.html) | Format, minify, validate, sort keys, escape/unescape JSON |
| [JSON Minifier / Beautifier](tools/json-beautifier.html) | Beautify or minify JSON with syntax highlighting |
| [Word & Character Counter](tools/word-counter.html) | Count words, characters, sentences, paragraphs, reading time |
| [Text Case Converter](tools/text-case.html) | Convert between camelCase, snake_case, UPPER, Title Case, etc. |
| [Find & Replace](tools/find-replace.html) | Search and replace text with regex, case sensitivity, whole word |
| [Lorem Ipsum Generator](tools/lorem-ipsum.html) | Generate placeholder text (words, sentences, paragraphs) |
| [Whitespace Editor](tools/whitespace-editor.html) | Visualize, remove, and convert whitespace characters |
| [Character Map](tools/character-map.html) | Browse and copy Unicode characters and symbols |

### Encoding & Decoding
| Tool | Description |
|------|-------------|
| [Base64 Encoder / Decoder](tools/base64.html) | Encode/decode text and files to Base64 |
| [URL Encoder / Decoder](tools/url-encoder.html) | Encode/decode URLs and components |
| [HTML Entity Encoder](tools/html-entity-encoder.html) | Encode/decode HTML entities |
| [JWT Decoder](tools/jwt-decoder.html) | Decode and inspect JSON Web Tokens |
| [Hash Generator](tools/hash-generator.html) | Generate MD5, SHA-1, SHA-256, SHA-512 hashes |

### Conversion Tools
| Tool | Description |
|------|-------------|
| [CSV to JSON](tools/csv-json.html) | Convert between CSV and JSON |
| [XML to JSON](tools/xml-json.html) | Convert between XML and JSON |
| [HTML to Markdown](tools/html-markdown.html) | Convert between HTML and Markdown |
| [Markdown to HTML](tools/markdown-html.html) | Convert Markdown to styled HTML |
| [Number Base Converter](tools/base-converter.html) | Binary, octal, decimal, hex, base-32, base-64 |
| [Unit Converter](tools/unit-converter.html) | Length, weight, temperature, speed, volume, area, data |
| [Timestamp Converter](tools/timestamp-converter.html) | Unix timestamps ↔ date formats with live clock |
| [Percentage Calculator](tools/percentage-calc.html) | Percentages, discounts, tip calculator |

### Design Tools
| Tool | Description |
|------|-------------|
| [Color Picker & Converter](tools/color-picker.html) | Pick colors, convert HEX/RGB/HSL, generate shades |
| [Color Converter](tools/color-converter.html) | Convert between HEX, RGB, HSL with live preview |
| [Color Palette Generator](tools/color-palette.html) | Generate harmonious palettes (analogous, complementary, etc.) |
| [Color Shades Generator](tools/color-shades.html) | Generate shades and tints from any base color |
| [CSS Gradient Generator](tools/css-gradient.html) | Linear, radial, conic gradients with presets |
| [Box Shadow Generator](tools/box-shadow.html) | Visual CSS box shadow builder |
| [Favicon Generator](tools/favicon-generator.html) | Generate favicons in multiple sizes from a letter/emoji |
| [Placeholder Image Generator](tools/placeholder-image.html) | Generate placeholder images in any dimension |

### Code Tools
| Tool | Description |
|------|-------------|
| [Regex Tester](tools/regex-tester.html) | Test regular expressions with live matching and groups |
| [Regex Cheat Sheet](tools/regex-cheatsheet.html) | Searchable quick reference for regex patterns |
| [Cron Expression Parser](tools/cron-parser.html) | Parse, describe, and preview cron schedules |
| [CSS Minifier / Beautifier](tools/css-minifier.html) | Minify or beautify CSS |
| [JS Minifier / Beautifier](tools/js-minifier.html) | Minify or beautify JavaScript |
| [HTML Minifier / Beautifier](tools/html-minifier.html) | Minify or beautify HTML |
| [Text Diff Checker](tools/text-diff.html) | Compare two texts and highlight differences |
| [Markdown Preview](tools/markdown-preview.html) | Live Markdown preview with toolbar |

### Utility Tools
| Tool | Description |
|------|-------------|
| [Password Generator](tools/password-generator.html) | Secure passwords with strength meter and entropy analysis |
| [QR Code Generator](tools/qr-code.html) | Generate QR codes with custom colors and sizes |
| [UUID Generator](tools/uuid-generator.html) | Generate v4 and v1 UUIDs in batch |
| [Image to Base64](tools/image-to-base64.html) | Convert images to Base64 data URLs |
| [IP Info Lookup](tools/ip-lookup.html) | Look up public IP address info |
| [Stopwatch & Timer](tools/stopwatch.html) | Stopwatch with laps and countdown timer |

---

## How to Use

### GitHub Pages
Visit the live site: **[jajajkones.github.io/protonflix/tools/](https://jajajkones.github.io/protonflix/tools/)**

The root URL serves the original ProtonFlix page: **[jajajkones.github.io/protonflix/](https://jajajkones.github.io/protonflix/)**

### Local
Clone the repo and open any tool file directly in your browser:
```bash
git clone https://github.com/jajajkones/protonflix.git
cd protonflix/tools
open json-formatter.html  # or just double-click the file
```

### Self-Host
Upload the `tools/` folder to any static hosting service (Netlify, Vercel, Cloudflare Pages, S3, etc.)

---

## Features

- **Zero dependencies** — every tool is a single standalone HTML file
- **No build step** — just open in a browser
- **No server** — all processing happens client-side
- **No tracking** — your data never leaves your browser
- **Dark theme** — consistent UI across all tools
- **Responsive** — works on desktop and mobile
- **Copy to clipboard** — one-click copy on most outputs
- **Fast** — instant results, no loading screens

---

## Tech Stack

- Vanilla HTML, CSS, and JavaScript
- CSS Custom Properties (variables)
- Web Crypto API (for hashing)
- Canvas API (for image/QR generation)
- No frameworks. No libraries. No bloat.

---

## Contributing

1. Fork the repo
2. Create a new branch: `git checkout -b tool-name`
3. Add your tool as `tools/your-tool.html`
4. Follow the existing dark theme style
5. Keep it self-contained (single HTML file)
6. Submit a PR

### Tool Requirements
- Must be a single `.html` file with no external dependencies
- Must include `<a href="index.html">← Back to Tools</a>` in the header
- Must use the dark theme (`#0a0a0a` background, `#111` surfaces, `#222` borders)
- Must be responsive

---

## License

MIT License — see [LICENSE](LICENSE) for details.

---

## Acknowledgments

Built as a free resource for the developer community. Star the repo if you find it useful.
