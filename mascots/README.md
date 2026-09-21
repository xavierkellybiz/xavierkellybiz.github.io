# Easy mascots (landing page) — Roo & Zest

Drop the official illustration exports here as transparent PNGs named
`<name>-<pose>.png` (e.g. `roo-wave.png`, `zest-celebrate.png`), then register the path in
`src/components/Mascot.tsx` → `MASCOTS`:

```ts
const MASCOTS = {
  "roo-wave": "/mascots/roo-wave.png",
  "roo-motorbike": "/mascots/roo-motorbike.png",
  "zest-wave": "/mascots/zest-wave.png",
  "zest-celebrate": "/mascots/zest-celebrate.png",
  // …
};
```

Every `<Mascot>` placement picks it up automatically. Until a pose is registered, a calm
on-brand placeholder (gradient disc + initial) renders — no missing-asset 404s.

Current placements: Hero (roo · wave, peeking by the phone), Results "Wall of love"
(zest · celebrate), Footer (zest · wave, "see you at the next good choice").
Roo rides on green, Zest brings the orange.
