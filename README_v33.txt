YJS Upgrade v33 — Coronation now sets Operator Mode + Owner Claim (A+B polish continuation)

What this does:
- Adds/updates coronation.html:
  - "Complete Coronation" sets device-local flags: yjsCoronated=true, yjs_phrase_ok=true
  - Includes an Owner Claim input (default key: PRIESTESS) that also sets yjsOwner=true and vault flags
  - Shows status text so you can see what the device is holding

Deploy:
1) Unzip
2) Upload coronation.html to your repo root (replace if it exists)
3) Commit
4) Visit:
   /coronation.html

Notes:
- No backend. Everything is device-local on purpose.
- If you want shared identity across devices later, we add a backend later.
