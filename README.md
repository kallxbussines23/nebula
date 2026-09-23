# Nebula Browser V1.1.1 — Chromium Shell + Puri.li Search

Built from the V1.1 Chromium Shell source.

- Persistent real Chromium via Puppeteer.
- Address bar is fully editable; focus selects the current URL so Backspace/Ctrl+A works.
- Address value is not overwritten while the user is editing.
- HTTP(S) URLs navigate directly.
- Bare domains become HTTPS.
- Non-URL text searches through Puri.li.
- One-finger touch swipes in the viewport are bridged to Chromium wheel scrolling.
- Viewport is clipped to the Nebula shell width/height so it cannot create horizontal overflow.
- No WebRTC and no custom browser engine.
