# Peter’s Plants 🪴

A watering checklist for plant-sitting Peter’s apartment — **one card for every single plant** (59 of them),
built from his July 5 walkthrough: photos, video stills, and his verbatim instructions.

**Live:** https://ashtyngon.github.io/peter-plants/

- Every plant has its own cropped photo, room, schedule, and Peter’s exact words.
- Tap **Watered** — cards turn amber when due, red when overdue, green when good.
- **Synced:** progress is shared through a common JSON store — every device and every person
  looking at the page sees the same state (merge-on-write, so two people can water at once).
- localStorage keeps it working offline; it re-merges when back online.
- "Check-first" pots (the clear-pot snake plant, the mystery pot under plastic) get a **Checked**
  button instead — Peter's rule is *look first, water only if dry*.
- The sad mint pot officially "doesn't like anything" and has nothing to do. It got a card anyway.

Static page, vanilla JS, no build, no dependencies. The WiFi sign in one source photo is pixelated.
Rebuilt from group cards to per-plant cards on July 20 (videos removed by request — replaced with
frame-extracted crops; instructions recovered via Whisper transcription + Gemini video cross-check).
