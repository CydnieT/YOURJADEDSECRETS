YJS Upgrade v32 — Device Polish (A) + Owner Override (B)

A) Polished fallback copy
- Replaces dev text like "how to drop" with intentional messaging.

A) Device-aware micro-line
- Adds: "Access is remembered per device/browser. New device = new door." on gated pages.

B) Owner Override (no backend)
- Adds owner.html
- Enter key to set unlock flags on THIS device (localStorage)
- Then jump to Rooms and everything behaves unlocked.

Deploy:
1) Unzip
2) Upload/replace ALL files to your GitHub repo root (recommended for consistency)
   At minimum: owner.html, inner-chamber.html, gatekeeper.html, rooms.html
3) Commit
4) On any new device: open /owner.html and enter the key.

Default owner key: PRIESTESS
(Change it in owner.html if you want.)
