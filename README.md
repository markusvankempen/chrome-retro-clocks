# RetroClocks

<p align="center">
  <img src="icons/icon128.png" alt="RetroClocks" width="96" height="96">
</p>

<p align="center">
  <strong>Retro clocks for your new tab.</strong><br>
  Split-flap cards, Nixie tubes, seven-segment, yellow dots, Lego, and origami.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/chrome-Manifest%20V3-4285F4" alt="Manifest V3">
  <a href="PRIVACY.md"><img src="https://img.shields.io/badge/privacy-local%20only-6f42c1" alt="Privacy: local only"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-Apache%202.0-16c060" alt="Apache 2.0"></a>
</p>

RetroClocks replaces Chrome’s new tab with a retro clock. Pick a face: split-flap cards, glowing Nixie tubes, a seven-segment display, yellow dots, Lego bricks, or origami. Hours and minutes, optional seconds, and the date. Click the clock and the digits scramble, then land back on the time.

Settings fill the browser window, with a live preview beside the tabs.

| Tab | What you set |
| --- | --- |
| Clock | Face, size, and flap sound when the face is split-flap |
| Time & date | 12-hour or 24-hour, seconds, colon blink, timezone, and the date |
| Look | Background, number, and colon colours. A colour for each digit on seven-segment, origami, and Lego |
| About | Author, export, and import of a settings file |

Flap sound plays two short recordings, one then the other, each time a card flips. The clips are in [`sounds/flap/`](sounds/flap/). Sound stays off until you turn it on.

Chrome lets one extension own the new tab. If another new-tab clock is installed, choose which one you want under `chrome://extensions`.

---

## Privacy

The extension uses the storage permission only. It does not collect accounts, browsing history, or analytics. It does not phone home. Settings stay in Chrome sync, or on this computer. An exported settings file stays where you save it.

Full text: [PRIVACY.md](PRIVACY.md) · [privacy.html](privacy.html)

Store privacy policy URL:

https://github.com/markusvankempen/chrome-retro-clocks/blob/main/PRIVACY.md

---

## Get the extension

Current version: **1.1.0** — see [CHANGELOG.md](CHANGELOG.md). The store package is attached to the [1.1.0 release](https://github.com/markusvankempen/chrome-retro-clocks/releases/tag/v1.1.0).

Install from the Chrome Web Store when the listing is live. This repository is the homepage, privacy policy, licence, icons, and store assets.

**Homepage:** [github.com/markusvankempen/chrome-retro-clocks](https://github.com/markusvankempen/chrome-retro-clocks)  
**Author:** [github.com/markusvankempen](https://github.com/markusvankempen) · [markusvankempen.github.io](https://markusvankempen.github.io/)

Screenshots from the clock are in [`store/`](store/).

---

## Author

**Markus van Kempen**

No bug 🐛 too small, no syntax too weird

https://markusvankempen.github.io/

---

## Licence

[Apache 2.0](LICENSE) — Copyright (c) 2026 Markus van Kempen.
