# Math Adventure 🐉🦄

A gamified math missions dashboard for kids — Roblox-style world map, XP,
stars, pet hatching, and a printable hero certificate.

- **Play**: `index.html` (hosted on GitHub Pages)
- **Login**: Firebase Auth (email/password) — the Guardian Gate 🔒
- **Progress**: synced per-player to Firestore (`progress/{uid}`), with
  localStorage fallback for offline play
- **Missions**: defined in the `UNITS` data block in `index.html`. New
  assignment packs are added as new units/worlds.
