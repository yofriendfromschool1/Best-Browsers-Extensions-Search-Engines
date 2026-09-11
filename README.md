# 🛡️ Best Browsers & Extensions

A curated list of privacy-respecting browsers, must-have extensions, search engines, and link-bypass tools.

## Table of Contents
- [Browsers](#browsers)
  - [Android](#android)
  - [iOS](#ios)
  - [Firefox Forks (Desktop)](#firefox-forks-desktop)
  - [Chromium (Desktop)](#chromium-desktop)
- [Browser Extensions](#browser-extensions)
- [Search Engines](#search-engines)
- [Short-Link Bypass Scripts](#short-link-bypass-scripts)

---

## Browsers

### Android

| Browser | Link | Notes |
|---------|------|-------|
| **IronFox** | https://ironfoxoss.org/ | Hardened Firefox fork (successor to Mull) |
| **Cromite** | https://www.cromite.org/ | Hardened Chromium fork with built-in adblock (successor to Bromite) |
| **Vanadium** | https://grapheneos.org/usage/web-browsing/ | Hardened Chromium — only available on GrapheneOS |
| **Brave** | https://brave.com/ | |
| **Tor Browser** | https://www.torproject.org/download/ | |
| **Fennec F-Droid** | https://f-droid.org/en/packages/org.mozilla.fennec.fdroid/ | Firefox with telemetry/proprietary bits removed |
| **Iceraven** | https://github.com/iceweasel/Iceraven-browser | Firefox fork with extra features and settings |
| **DuckDuckGo Browser** | https://duckduckgo.com/android | |

> 💡 Firefox-based Android browsers (IronFox, Fennec, Iceraven) support desktop extensions, including **uBlock Origin**. Chromium Android browsers don't support extensions at all.
> 💡 Prefer installing apps via [F-Droid](https://f-droid.org/) where available.

### iOS

| Browser | Link | Notes |
|---------|------|-------|
| **Orion** | https://apps.apple.com/us/app/orion-browser-by-kagi/id1484498200 | WebKit browser by Kagi, supports Firefox/Chrome extensions |

### Firefox Forks (Desktop)

| Browser | Link | Notes |
|---------|------|-------|
| **LibreWolf** | https://librewolf.net/ | Firefox with privacy hardening out of the box |
| **Mullvad Browser** | https://mullvad.net/en/browser | Hardened by Mullvad + Tor Project |
| **Tor Browser** | https://www.torproject.org/download/ | For anonymity |
| **Zen Browser** | https://zen-browser.app/ | Arc-like Firefox fork (https://github.com/JustAdumbPrsn/Zen-Nebula) LOVE THIS MODDED VERRR |
| **Sine** | https://github.com/CosmoCreeper/Sine | Not a browser — themes, if you have a flatpak install of a browser: https://github.com/CosmoCreeper/Sine/releases/tag/v2.3 flatpak |
| **arkenfox user.js** | https://github.com/arkenfox/user.js | Not a browser — config file to harden Firefox yourself |

### Chromium (Desktop)

| Browser | Link | Notes |
|---------|------|-------|
| **Brave** | https://brave.com/ | ⚠️ Don't use Brave's built-in Tor mode — use the actual Tor Browser |
| **Brave Origin** | https://brave.com/origin/ | Brave without the AI/crypto/bloat. Free on Linux, paid on other OSes |
| **Helium** | https://helium.computer | Minimal ui, ships with Ublock Origin, very privacy/security based. |

**Brave Origin unlocker scripts (unofficial):**

- All OSes:
  - https://github.com/ChaoticSi1ence/SlimBrave-Neo
- Windows:
  - https://github.com/bharsgo/brave-debloater
  - https://github.com/TahaHydra/Brave-Free-Origin
  - https://github.com/ObjectAscended/brave-origin-unlocker
  - https://github.com/aivrar/brave-origin-for-windows
- macOS:
  - https://github.com/bharsgo/brave-debloater
  - https://github.com/Johnny-Kao/brave-free-origin-macos
  - https://github.com/ObjectAscended/brave-origin-unlocker

---

## Browser Extensions

### Ad & Tracker Blocking

| Extension | Firefox | Chromium | Notes |
|-----------|---------|----------|-------|
| **uBlock Origin** | https://addons.mozilla.org/firefox/addon/ublock-origin/ | https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm | ⚠️ Chrome's Manifest V3 cripples it — on Chromium use [uBO Lite](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh) instead |
| **NoScript** | https://addons.mozilla.org/firefox/addon/noscript/ | https://chromewebstore.google.com/detail/noscript/doojmbjmlfjjnbmnoijecmcbfeoakpjm | |
| **Privacy Badger** | https://addons.mozilla.org/firefox/addon/privacy-badger17/ | https://chromewebstore.google.com/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp | |
| **Mullvad Extension** | https://mullvad.net/en/download/browser/extension | — | Limits HTML5/JS tracking |
| **DuckDuckGo Privacy Essentials** | https://addons.mozilla.org/firefox/addon/duckduckgo-for-firefox/ | — | Only recommended for Firefox |

### Anti-Fingerprinting

| Extension | Firefox | Chromium | Notes |
|-----------|---------|----------|-------|
| **Canvas Blocker** | https://addons.mozilla.org/firefox/addon/canvasblocker/ | https://chromewebstore.google.com/detail/canvas-blocker-fingerprin/nomnklagbgmgghhjidfhnoelnjfndfpd | |
| **WebRTC Disabler** | https://addons.mozilla.org/firefox/addon/happy-bonobo-disable-webrtc/ | https://chromewebstore.google.com/detail/webrtc-control/fjkmabmdepjfammlpliljpnbhleegehm | Prevents WebRTC IP leaks |
| **User Agent Switcher** | https://addons.mozilla.org/firefox/addon/uaswitcher/ | https://chromewebstore.google.com/detail/user-agent-switcher-for-c/djflhoibgkdhkhhcedjiklpkjnoahfmg | |
| **Smart Referer** | https://addons.mozilla.org/firefox/addon/smart-referer/ | https://chromewebstore.google.com/detail/referer-control/hnkcfpcejkafcihlgbojoidoihckciin | Chromium version is "Referer Control" |
| **CSS Exfil Protection** | https://addons.mozilla.org/firefox/addon/css-exfil-protection/ | https://chromewebstore.google.com/detail/css-exfil-protection/ibeemfhcbbikonfajhamlkdgedmekifo | Blocks CSS data exfiltration |

### Local CDN (faster + less tracking)

| Extension | Firefox | Chromium | Notes |
|-----------|---------|----------|-------|
| **Decentraleyes** | https://addons.mozilla.org/firefox/addon/decentraleyes/ | https://chromewebstore.google.com/detail/decentraleyes/npnfnfekfhldbggilgeeclgndijakdn | Serves common libraries locally |
| **LocalCDN** | https://addons.mozilla.org/firefox/addon/localcdn-fork-of-decentraleyes/ | https://chromewebstore.google.com/detail/localcdn/lpeckldiaajlnihkkepgaddnnnebhkah | Fork of Decentraleyes with more coverage |

### URL Cleaning

| Extension | Firefox | Chromium | Notes |
|-----------|---------|----------|-------|
| **ClearURLs** | https://addons.mozilla.org/firefox/addon/clearurls/ | https://docs.clearurls.xyz/1.26.1/#download | Strips tracking params from URLs |
| **Neat URL** | https://addons.mozilla.org/firefox/addon/neat-url/ | https://chromewebstore.google.com/detail/neat-url/jchobbjgibcahbheicfocecmhocglkco | |
| **MetaClean for Gmail** | https://addons.mozilla.org/firefox/addon/metaclean-for-gmail-v215/ | https://chromewebstore.google.com/detail/metaclean-for-gmail/ifhaebfhlkmamahknibbbpfddoeidimi | Strips tracking from links in Gmail |

### YouTube

| Extension | Link | Notes |
|-----------|------|-------|
| **SponsorBlock** | https://sponsor.ajay.app/ | Skips sponsor segments |
| **DeArrow** | https://dearrow.ajay.app/ | Replaces clickbait titles/thumbnails |
| **Return YouTube Dislike** | https://returnyoutubedislike.com/ | Restores dislike counts |

### Email Encryption & Passwords

| Extension | Link | Notes |
|-----------|------|-------|
| **FlowCrypt** | https://flowcrypt.com/ | PGP for Gmail |
| **Mailvelope** | https://mailvelope.com/en | PGP for webmail |
| **KeePassXC** | https://keepassxc.org/download/#browser | ⚠️ Requires the desktop app installed |

### Utilities

| Extension | Firefox | Chromium | Notes |
|-----------|---------|----------|-------|
| **Dark Reader** | https://addons.mozilla.org/firefox/addon/darkreader/ | https://chromewebstore.google.com/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh | |
| **Zen Internet** | https://addons.mozilla.org/en-US/firefox/addon/zen-internet/ | firefox only duh zen | |
| **Bonjourr** | https://addons.mozilla.org/en-US/firefox/addon/bonjourr-startpage/ | Firefox only, aesthetic new tab page. | |
| **Search by Image** | https://addons.mozilla.org/firefox/addon/search_by_image/ | https://chromewebstore.google.com/detail/search-by-image/cnojnbdhbhnkbcieeekonklommdnndci | |
| **Violentmonkey** | https://addons.mozilla.org/firefox/addon/violentmonkey/ | https://chromewebstore.google.com/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag | Userscript manager |
| **FastForward** | https://fastforward.team/ | Skips link shortener countdowns |
| **Chrome Mask** | https://addons.mozilla.org/firefox/addon/chrome-mask/ | Firefox-only — fixes sites that break on non-Chrome browsers |
| **Chrome2Fox** | https://addons.mozilla.org/en-US/firefox/addon/chrome2fox/ | Firefox-only — Makes google chrome webstore converted to firefox extension. |

---

## Search Engines

URL templates for setting a **custom search engine** in your browser (`%s` = your query).

| Engine | URL | Notes |
|--------|-----|-------|
| **SearXNG** | https://searx.space/ | Best option — open-source metasearch |
| **Startpage** | https://www.startpage.com/sp/search?query=%s&cat=web&pl=opensearch | |
| **Brave Search** | https://search.brave.com/search?q=%s | |
| **Mullvad Leta** | https://leta.mullvad.net/?q=%s | Requires a Mullvad VPN connection |
| **DuckDuckGo** | https://duckduckgo.com/?t=ffab&q=%s&atb=v443-1 | Least recommended — mainly useful for image search |
| **Google** | https://www.google.com/search?q=%s | ⚠️ Worst option — only when you really need it or for reverse image search |

### Tor-only

| Engine | Link |
|--------|------|
| **Ahmia** | https://ahmia.fi |

---

## Short-Link Bypass Scripts

### Userscripts (install via Violentmonkey or Tampermonkey)

- **Bypass All Shortlinks** — https://greasyfork.org/en/scripts/431691-bypass-all-shortlinks
- **Bypass All Shortlinks (Debloated)** — https://codeberg.org/gongchandang49/bypass-all-shortlinks-debloated
- **Bypass-VIP** — https://raw.githubusercontent.com/bypass-vip/userscript/refs/heads/main/bypass-vip.user.js
- **TRW Timer Bypass** — https://trw.lat/install/userscript/u.user.js?v=L
- **Hook-JS Timer** — https://palerock.cn/node-service/scripts/install/@hook-js_timer/hook.timer.user.js
- **adBypass** — https://api2.adbypass.org/userscript/download/bypass.user.js
- **m-links** — https://api.yuumari.com/dl/m-links.user.js
- **Bypass Freedlink Countdown** — https://greasyfork.org/en/scripts/522735-bypass-freedlink-countdown

### Web Tools

- **skipped.lol** — https://skipped.lol/

### Extensions

- **BypassKit (Link Unlocker)** — https://chromewebstore.google.com/detail/bypasskit-link-unlocker/aiddkahemeniiedmpfblodnmcjoelbjl
