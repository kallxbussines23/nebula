# Nebula V1 — Chromium Shell

Nebula V1 wraps a real Chromium instance with a custom mobile browser UI. It does not implement a browser engine, WebRTC, or a custom renderer.

Architecture: Nebula UI -> WebSocket controller -> persistent Chromium -> Internet.

Deploy the repository as a Railway Docker service. `/health` reports the runtime version. `CHROMIUM_EXECUTABLE` defaults to `/usr/bin/chromium`.

V1 includes navigation, tabs, back/forward/reload, click, keyboard commands, touch-to-scroll, persistent pages, and basic SSRF/private-network blocking.
